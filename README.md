# DEFT2013 Tâche 2 : HiTALru NaTALmura & TALnus TArLsen


RIOLE Remy - CALLET Elliot



## Description de la tâche



	L'objectif est de prédire le type d'un plat à partir d'informations telles que la recette, le titre, ou encore les ingrédients. Il s'agit d'une tâche de classification. Voici un exemple de donnée avec lesquels nous travaillons : 
 doc_id : recette_217204.xml
 titre : Crêpes au canard laqué
 type : Entrée
 difficulte : Moyennement difficile
 cout : Moyen
 ingredients : - 90 g de farine - 45 g de maïzena [...] - 9 cl de sauce hoisin
 recette : Couper finement le blanc [...] une salade verte.



## Statistiques corpus



	Nombre de document de train/dev/test

	Répartition des étiquettes dans chacun des sous-ensemble



## Méthodes proposées



### Run1: baseline (méthode de référence)

  - Nous avons choisi de simplement prédire la classe majoritaire. Dans notre cas, il s'agit de la classe "Plat principal", qui représente environ 47% de notre corpus d'entrainement. Nous n'utilisons donc pas de descripteur particulier, ni de classifieur.

### Run2: SVC Tf-Idf

  - 

### Run3: NOMMETHODE

### Run4: NOMMETHODE (pour aller plus loin)



## Résultats



| Run      | f1 Score |

| -------- | --------:|

| baseline |  15,2 |

| METH 2   |   6,8 |

| METH 3   |  50,8 |

| METH 4   |  70,2 |



### Analyse de résultats

	

	Pistes d'analyse:

	* Combien de documents ont un score de 0 ? de 0.5 ? de 1 ? (Courbe ROC)

	* Y-a-t-il des régularités dans les document bien/mal classifiés ?

	* Où est-ce que l'approche se trompe ? (matrice de confusion)

	* Si votre méthode le permet: quels sont les descripteurs les plus décisifs ?
