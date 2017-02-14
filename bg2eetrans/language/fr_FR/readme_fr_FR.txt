Ce mod installe une traduction partielle des textes pour BG2EE � partir des textes de BG II + ToB (original) et de la traduction de BGEE (V2.3).

Remarque : le mod est bas� sur une recherche de correspondance entre les textes en anglais de BG2EE et ceux de BG II + ToB et de BGEE date des versions 2.3 de BG2EE et de BGEE. Par cons�quent il ne remplace en fran�ais que les textes suffisamment proches en anglais. Lorsque les textes de BG2EE ont trop chang� par rapport � BG II + ToB, le mod pr�f�re pr�server le texte anglais plut�t que remplacer par une traduction qui pourrait s'av�rer fausse, particuli�rement pour les aspects techniques du jeu (description des classes, kits, sorts, objets).

Par ailleurs le mod modifie la liste de langues disponibles dans BG2EE (V2.0 et sup�rieur) afin d'ajouter le fran�ais dans la liste.


Historique
----------
Remarque : la version s'�crit sous la forme X.Y.r�vision_du_jeu
La r�vision du jeu est la r�vision de BG2EE � partir de laquelle l'algorithme de recherche de correspondance de textes avec ceux de ToB et BGEE a �t� faite. Ce n'est pas n�cessairement la derni�re en cours. Cette r�vision n'a pas d'incidence sur la compatibilit� du mod avec une version particuli�re du jeu.
La cons�quence est que les textes ajout�s par Beamdog apr�s la r�vision indiqu�e ne sont pas pris en compte et resteront en anglais quoi qu'il arrive. En cas de modification de texte, le mod ne tiendra pas non plus compte du changement. N�anmoins le risque est assez faible qu'il y ait eu des changements remettant en cause la validit� du choix de reprendre la traduction d'origine ou de laisser le texte en anglais.

V0.1.2050 : janvier 2014
- version non diffus�e ayant permis de g�n�rer les fichiers dialog.tlk et dialogF.tlk mis � disposition pour les versions 1.2 et ult�rieurement 1.3 de BG2EE

V0.2.2064
- prise en compte de BG2EE V2.x ; ajout de la langue fran�aise dans BGEE.lua afin qu'elle soit accessible dans l'�cran des options
- ajout du fichier de traduction de l'interface du jeu pour BG2EE V2.x

V0.3.2064
- correction du fichier de traduction de l'interface
- diff�rentiation Windows / Linux et Mac sur la mani�re de lancer l'installation des textes (retour de zelurker)
- compl�ment de d�tection d'erreur pour signaler l'utilisation d'une version insuffisante de WeiDU pour BG2EE V2.x

v0.4.67.3
- r�cup�ration d'une centaine de traductions depuis BGEE V2.3.67.3
- ajout de notes sur la version fran�aise (id�e de zelurker)
- nombreuses corrections de correspondances de textes gr�ce aux efforts de dricks, zelurker, Luren et Freddy_Gwendo
  * des correspondances inexactes ont �t� corrig�es
  * des correspondances nouvelles ont �t� v�rifi�es, ce qui augmente le nombre de textes traduits
  * restauration de voix et de sons ayant disparu ou incorrects (notamment sur des personnages recrutables)

v0.5.67.3
- Modification de la r�cup�ration de texte � partir de BGEE pour qu'elle ne prenne pas le pas sur de meilleurs textes trouv�s dans ToB
- Nombreuses am�liorations et corrections diverses de Freddy_Gwendo
  * respect de l'affichage avec ou sans majuscule initiale pour les noms de kits
  * corrections de mots, uniformisation avec les EE (ensorceleur, cavalier), retraits des "Utilisable par" restants
  * uniformisation de l'affichage des bonus des armes +n (sans espace)
  * des correspondances nouvelles ont �t� v�rifi�es, ce qui augmente le nombre de textes traduits, en particulier pour les objets

v0.6.67.3
- Corrections diverses propos�es par Freddy_Gwendo
- Refonte compl�te de la gestion des textes ajout�s par BG2EE (au-del� de 74106) : il s'agit d�sormais d'une traduction v�rifi�e couvrant environ 900 textes
- Dans cette partie BG2EE, les r�cup�rations de textes simples tels que "merci", "au revoir", "qu'est ce que vous voulez ?" ont �t� neutralis�es (apport quasi nul, risque de mauvais adaptation au contexte, etc.)
