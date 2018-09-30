Ce mod installe une traduction partielle des textes pour BG2EE � partir des textes r�cup�r�s de BG II + ToB (original) et des traductions de BGEE (V2.5) et IWDEE (V2.5) mais �galement une traduction d'une partie des textes ajout�s dans BG2EE.

Remarque : le mod est bas� sur une recherche de correspondance entre les textes en anglais de BG2EE et ceux de BG II + ToB et de BGEE date des versions 2.3 de BG2EE et de BGEE. Par cons�quent il ne remplace en fran�ais que les textes suffisamment proches en anglais. Lorsque les textes de BG2EE ont trop chang� par rapport � BG II + ToB, le mod pr�f�re pr�server le texte anglais plut�t que remplacer par une traduction qui pourrait s'av�rer fausse, particuli�rement pour les aspects techniques du jeu (description des classes, kits, sorts, objets). Une partie de ces textes non r�cup�r�s a �t� trait� � la main, soit en confirmant par un humain que le texte original convenait soit en modifiant le texte pour assurer une bonne traduction.

Par ailleurs le mod modifie la liste de langues disponibles dans BG2EE (V2.0 et sup�rieur) afin d'ajouter le fran�ais dans la liste et fournit le fichier de traduction de l'interface du jeu.


Historique
----------
Remarque : la version s'�crit sous la forme X.Y.r�vision_du_jeu
La r�vision du jeu est la r�vision de BG2EE � partir de laquelle l'algorithme de recherche de correspondance de textes avec ceux de ToB et BGEE a �t� faite ou la derni�re pour laquelle les textes ajout�s ou modifi�s ont �t� pris en compte. Ce n'est pas n�cessairement la derni�re en cours. Cette r�vision n'a pas d'incidence sur la compatibilit� du mod avec une version particuli�re du jeu.
La cons�quence est que les textes ajout�s par Beamdog apr�s la r�vision indiqu�e ne sont pas pris en compte et resteront en anglais quoi qu'il arrive. En cas de modification de texte, le mod ne tiendra pas non plus compte du changement. N�anmoins le risque est assez faible qu'il y ait eu des changements remettant en cause la validit� du choix de reprendre la traduction d'origine ou de laisser le texte en anglais (pour les textes du jeu original).

V0.1.2030 - 23 d�cembre 2013
- version non diffus�e ayant permis de g�n�rer les fichiers dialog.tlk et dialogF.tlk mis � disposition pour les versions 1.2 et ult�rieurement 1.3 de BG2EE

V0.2.2064 - 28 mai 2016
- prise en compte de BG2EE V2.x ; ajout de la langue fran�aise dans BGEE.lua afin qu'elle soit accessible dans l'�cran des options
- ajout du fichier de traduction de l'interface du jeu pour BG2EE V2.x

V0.3.2064
- correction du fichier de traduction de l'interface
- diff�rentiation Windows / Linux et Mac sur la mani�re de lancer l'installation des textes (retour de zelurker)
- compl�ment de d�tection d'erreur pour signaler l'utilisation d'une version insuffisante de WeiDU pour BG2EE V2.x

v0.4.67.3 - 18 d�cembre 2016
- r�cup�ration d'une centaine de traductions depuis BGEE V2.3.67.3
- ajout de notes sur la version fran�aise (id�e de zelurker)
- nombreuses corrections de correspondances de textes gr�ce aux efforts de dricks, zelurker, Luren et Freddy_Gwendo
  * des correspondances inexactes ont �t� corrig�es
  * des correspondances nouvelles ont �t� v�rifi�es, ce qui augmente le nombre de textes traduits
  * restauration de voix et de sons ayant disparu ou incorrects (notamment sur des personnages recrutables)

v0.5.67.3 - 8 janvier 2017
- modification de la r�cup�ration de texte � partir de BGEE pour qu'elle ne prenne pas le pas sur de meilleurs textes trouv�s dans ToB
- nombreuses am�liorations et corrections diverses de Freddy_Gwendo
  * respect de l'affichage avec ou sans majuscule initiale pour les noms de kits
  * corrections de mots, uniformisation avec les EE (ensorceleur, cavalier), retraits des "Utilisable par" restants
  * uniformisation de l'affichage des bonus des armes +n (sans espace)
  * des correspondances nouvelles ont �t� v�rifi�es, ce qui augmente le nombre de textes traduits, en particulier pour les objets

v0.6.67.3 - 15 f�vrier 2017
- corrections diverses propos�es par Freddy_Gwendo
- refonte compl�te de la gestion des textes ajout�s par BG2EE (au-del� de 74106) : il s'agit d�sormais d'une traduction v�rifi�e couvrant environ 900 textes
- dans cette partie BG2EE, les r�cup�rations de textes simples tels que "merci", "au revoir", "qu'est ce que vous voulez ?" ont �t� neutralis�es (apport quasi nul, risque de mauvais adaptation au contexte, etc.)

v0.7.16.6 - 29 septembre 2018
- ajout majeur de contenu traduit
  * Qu�te de Rasaad dans SoA : dialogues, lieux, personnages (des noms de cr�atures peuvent ne pas �tre traduits)
  * Sous-titre des voix pour le personnage principal et pour Rasaad
  * Objets ajout�s par BG2EE
  * Sorts ajout�s par BG2EE
- fichier L_fr_FR.lua d�sormais copi� dans override pour la compatibilit� avec des mods GUI touchant aux textes
- corrections/am�liorations diverses dans les textes repris de ToB (d�but de fusion de travaux 0 -> 500 environ)
- compl�ments de traduction pour BG2EE V2.5.16.6 (L_fr_FR.lua et de nouveaux textes dans BG2EE)
- proc�dure de d�sinstallation revue : il est possible de r�sinstaller le mod sans avoir du m�nage � faire � la main
