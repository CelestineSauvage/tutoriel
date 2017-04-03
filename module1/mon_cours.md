LANGUAGE: fr
CSS: http://culturenumerique.univ-lille3.fr/css/base.css" />
TITLE: Coucou
MENUTITLE: Salut
AUTHOR: Célestine SAUVAGE

# Plop

## Je rédige un quizz
```activité
::Quizz de l'extrême::
[markdown]
**Le matin :**
{ 
 ~%50% Je me lève
 ~%-50% Je me couche
 ~%50% Je mange & me lave les dents
 ~%-50% Je ne vais pas au travail
 #### Je me **lève**, je **mange** et me **lave les dents** évidemment !
 }
 
::Coucou::
[markdow]
**J'aime**
\n
- le chocolat
- les gâteaux
- les fruits

// Vraie/Faux (la bonne réponse est FAUX) avec feedback, le tout rédigé en texte simple

::Il n'existe qu'une façon seule façon de représenter numériquement un livre::
{F# représenter une information est le résultat de nombreux choix}


// Question ouverte (champ texte libre) avec feedback global, rédigé en texte simple

::Donnez des exemples de critères qui peuvent gouverner le choix d'une représentation numérique::
{#### la concision, la pertinence (permettre des traitements voulus), l'efficacité (les traitements sont réalisés rapidement, la confidentialité (l'accès aux données  peut être contrôlé),...}

// choix multiple avec feedback pour chaque réponse choisie, notez le choix du format markdown

::Les choix de représentations sont faits par::
[markdown]
{
~Les informaticiens#non pas seuls car intervient aussi l'utilisation métier des objets représentés
~Les experts métier#non pas seuls car il faut des spécialistes des données numériques et des algorithmes
=Les deux#oui et souvent aussi des chercheurs, des entreprises, ...
}

// question à choix multiple (1 seul bonne réponse), avec texte+feedback global rédigé en HTML

[html]<p>Que signifie <em>numérisation</em> ?</p>{
=<p>L'opération qui consiste à représenter sous forme de nombres une
information quelle qu'elle soit.</p>#<p>Oui !</p>
~<p>L'opération qui consiste à citer tous les nombres (1, 2, 3, 4, ….).</p>#<p>Non, citer tous les nombres c'est compter...</p>
####<p>La numérisation est l'opération qui consiste à représenter sous forme de nombres une information, quelle qu'elle soit.</p> }


// question à choix multiple et plusieurs bonnes réponses, pondérées de manière équivalente, mais une mauvaise réponse qui ne ramène pas de points, avec texte+feedback global rédigé en HTML

::Où sont les processeurs ?::
[html]<p>Parmi ces objets, quels sont ceux équipés de
processeur(s) \:</p>
{
~%16.66667%<p>tablettes</p>
~%16.66667%<p>smartphones</p>
~%16.66667%<p>box ADSL</p>
~%16.66667%<p>lecteur mp3</p>
~%16.66667%<p>ordinateur</p>
~%16.66667%<p>calculatrice</p>
~<p>aucun</p>#<p>Tous !</p>
####<p>Tous ces objets sont équipés de micro-processeurs !</p> }


// question de type 'Essay', ie. réponse texte libre, avec texte + feedback global (4#) rédigés en Markdown

::Le numérique dans la société::
[markdown]
Le numérique, un enjeu pour les **citoyens du XXIème siècle** ...
Le numérique nous concerne tous en tant que citoyen. Il permet de nouvelles choses en automatisant des procédures et en donnant accès à des données jusqu'ici inexploitables. Mais numérique n'est évidemment pas systématiquement synonyme de progrès. Il faut toujours réfléchir aux **finalités** des applications développées. Nous vous invitons à vous **documenter** et à réfléchir aux questions suivantes :
 - Dans la **gestion de l‘énergie**: qu'est-ce que la **troisième révolution industrielle** et pourquoi le numérique y contribue-t-il ?
- En **politique et média** : Qu'est-ce que la **vérification par les faits** (*fact-checking* en anglais) ? En quoi le numérique l'a rendue possible / facile ?
- En **citoyenneté** : Que signifie **vote électronique** et en quoi cela pose-t-il des questions essentielles ? Trouver au moins un *avantage* et un *inconvénient*.
Après avoir fait vos recherches, répondez aux questions posées en **quelques lignes** et en indiquant les **liens** où vous avez trouvé ces informations.
{####[markdown]
Voici quelques liens que nous vous proposons mais que vous avez sûrement trouvés par vous-même :
- À propos de la troisième révolution industrielle :
  - [Troisième révolution industrielle](http://fr.wikipedia.org/wiki/Troisième_révolution_industrielle)
  - [pasdecalais](http://www.latroisiemerevolutionindustrielleennordpasdecalais.fr)
- En **politique et média** : Qu'est-ce que la vérification par les faits (fact-checking en anglais) ? En quoi le numérique l'a rendue possible / facile ?
  - [vérification par les faits](http://fr.wikipedia.org/wiki/Vérification_par_les_faits)
- En **citoyenneté** : Que signifie vote électronique et en quoi cela pose-t-il des questions essentielles ? Trouver au moins un avantage et un inconvénient.
  - [arguments] (http://fr.wikipedia.org/wiki/Vote_électronique#Arguments_en_faveur)
}
```
