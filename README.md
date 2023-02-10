## README
Analyse audio et vidéo d'un débat suisse.

Découpage de l'émission :  
* 1 générique de début
* 1 reportage introductif (images montée avec une voix off - voix de la modératrice). 
* Le débat
* 1 générique de fin
	
On a accès à une seule vidéo et on fait l'hypothèse que notre analyse fonctionne sur l'ensemble des émissisions.
On a des annotations sur la vidéo qui servent à la classification, à l'évaluations.  
2 types d'annotations (les fichiers trs) :
* 06-11-22.tsr : déclaration des sections qui sont annotées (Speakers…) => exemple : speakers(=segment) qui correspondent aux noms des invités + les types de plans (Whole group - Plan d'ensemble).
On a ensuite les tours (changements de segments) avec un starttime / endtime. C'est qu'est ce qu'on voit à quel moment.
* 06-11-22_manual.trs : on a les vrais tours de parole (annotation du contenu audio). C'est qui parle quand.

Pour utiliser les annotations => outil ELAN 6.4
File / import / Transcriver File / Create a single tier… / aller chosiir le fichier trs / Lui donner le chemin de la vidéo 06-11-22.mp4
=> interface avec une ligne de temps en bas

# Objectif du TP

* Détection des sections de l'émission. 
 Générique : détection de la musique (commencer par faire MFCC (la musique a un timbre différent d'autres sons) puis tester autre chose). MFCC => bonne description du timbre.
 
* Analyse du bandeau (habillage + détection des noms). Identification des apparitions de texte dans le ruban débat qui indique le nom de l'intervenant et le métier + détection du thème de l'émission avec le bandeau.


	

