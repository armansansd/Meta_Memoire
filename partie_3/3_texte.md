Ce sont des scientifiques comme Douglas Engelbart et Alan Kay qui ont transformé l'écran d'ordinateur, en un espace où une collaboration entre humain et machine est possible. Et ce sont par la suite des [_hackers_][passionnés d'informatiques possédant une bonne compréhension des sytèmes] comme Steve Wozniak et Steve Jobs, créateurs d'Apple, qui ont enfermé ces concepts dans une machine afin de la rendre lucratif et de peser un poids sur le marché de la micro-informatique.(\)  
L'état actuel, [bipolaire][windows, Mac], du marché des systèmes d'exploitation , induit un enfermement des codes qui les composent et l'établissement d'une "mystique" de l'ergonomie maintenue par la publication régulière de [guide de design](img/interfaceguide) (_interface guideline_) par les dites entreprises.(\)
D'un réel contrôle de la machine nous sommes passée à une liberté virtuelle et coercitive, ou la vision de ce que doit être, va être, l'avenir de l'informatique nous est imposé. (\).   

Nous avons vu auparavant qu'une interface change la manière dont les utilisateurs pensent et interagissent les uns avec les autres. Les systèmes d'exploitations étaient pensés pour rester le plus abstrait et généraliste, permettant à tout un chacun de trouver son espace de liberté, d'adapter sa machine à ses besoins.  
Même si ces nouvelles limites, ces idiomes sont nécessaires à la compréhension et à l'utilisation des ordinateurs. Il est nécessaire de se pencher sur l'existence d'alternatives, de nouvelles approches forcées ou voulues. L'utilisation des logiciels libres en est une.
En 1970 de nombreuses entreprises se spécialisent dans le développement de programmes. Ce nouveau marché se développe rapidement et, pour engranger des bénéfices, elles ferment l'accès au [code source][le code source est le code lisible par un initié non transformé (compilé) en langage machine]en créant des contrats de non-divulgation, licences propriétaires. [Richard Stallman](img/Richard), alors étudiant au [MIT][Massachusset Institute of Technology], décide de créer un système d'exploitation totalement ouvert, où chacun pourra y ajouter sa ligne de code. En 1990 [_GNU_][_GNU’s Not UNIX _ acronyme imbriqué] [*](img/GNU)est prêt, mais il ne manque qu'une pièce au puzzle, le noyau. Le [noyau][kernel] d'un système est une partie qui gère la communication entre le matériel et le reste du programme. Linus Torvalds, un étudiant Finlandais, publie en 1991 le code (libre) d'un noyau qu'il vient d'écrire, ceci rend enfin le système GNU/Linux fonctionnel.
Stallman est aussi le fondateur de la _Free Software Foundation_, qui défend les intérêt des utilisateurs et des créateurs de logiciel sous licence libre. Ce qui lui permet aussi de définir, de manière solide, 4 libertés fondamentales (\):

* la liberté d'exécuter le programme   
* la liberté d'étudier le fonctionnement du programme et de l'adapter à ses besoins
* la liberté de redistribuer des copies du programme (vendre ou donner)
* la liberté d'améliorer le programme et de distribuer ces améliorations au public

L'utilisation de cette catégorie de logiciels, permet une nouvelle approche de ses/ces outils. Il faut, bien évidemment, être conscient que cette démarche  engage l'utilisateur à de nouvelles responsabilités et au  sacrifice d'une partie de son temps à un sapprentissage technique.  
Par ailleurs, la création de petit ordinateur, à des [prix accessible][20-25€], tel que le [Raspberry Pi](img/raspberry) (2011), on permit l'avènement de projet proposant au néophite de mettre la main à la pâte sans risquer de perdre toute ses données personnelles par une mauvaise manipulation. Ainsi Kano ou encore [Coder](img/coder)(de google), proposent de découvrir le monde de la programmation au travers d'une interface dédiée et épurée.

Il convient de noter l'avènement de nouveaux centres d'intérêt dans la création d'interfaces nommés l'écoconception logiciel.(\)
Ce terme a été amené par Frédéric Bordage sur son site (\) provient d'[une étude](img/grenit), qu'il a réalisée avec Frédéric Lohier en 2010(\), montrant  que même si consommation électrique des [processeurs][noyau de calcul de l'ordinateur] a diminué ces 30 dernières années, ces derniers ne peuvent ne pas subvenir aux besoins de l'utilisateur pendant 10ans. Une entreprise change en moyenne son matériel tous les 4/5 ans. Le problème se trouve du côté logiciels, ceux-ci sont en effet de plus en plus gourmand et demandent de plus en plus de puissance pour être exécuté. 
Les deux auteurs nous apprennent, par la suite, que le couple Microsoft Windows 7 et Office 2010 consomment quinze fois plus de puissance de calculs et 47 fois plus d'espace disque que le couple Win 98 + office 97, pour des utilisations similaires. Ce phénomène a un nom, l'obésicielle et une loi : la loi de [Wirth][le logiciel ralentit plus vite que le matériel n’accélère.].  
Une chose est sûre , les usages n'ont guère changé depuis 1998 et, par ailleurs les utilisateurs sont de plus en plus en recherche de sobriété comme le montre le succès d'outils comme google Drive ou Twitter.  

Une solution, amenée par les pratiques du libre et ses innovations, consisterait à optimiser les interfaces pour les limiter à des fonctions de bases, tout en autorisant l'ajout d'_ad-on_ afin que chacun puisse adapter son logiciel à ses usages.  
Cette "certaine marge d'indétermination" ne suppose pas que le logiciel est incomplet (\) mais qu'il laisse le champ libre à l'implémentation de [_plugins_ ][greffons complétant les fonctionnalités d'un logiciel]. Par exemple dans le navigateur web firefox quelques unes de ces extensions,tel que [Adblock plus](img/adb), sont devenus cultes. Ouvrir des programmes c'est leurs permettre d'évoluer, de suivre les avancés de leur temps, de se débarrasser de fonctions obsolètes pour en acquérir d'autre plus contemporaine. En outre de les rendre plus [pérenne][_Software_ le materiel mou]. 

Un autre domaine méconnu dans lequel de nombreuses innovations sont effectuées, est celui de l'accès aux technologies de l'information pour les handicapés. Diverses expérimentations et solutions ont vu le jour et permettent une autre approche (parfois plus sensible) du design des outils numériques.   
Les outils numériques exploitent des canaux correspondant à nos [sens][la parole et le geste], nous utilisons donc une interface multimodale composée d'un clavier, d'une souris, d'haut-parleur et d'un écran.  
Pour palier au handicap tout ces périphériques d'entrée et de sortie ont du être transposé / transcodé. Ainsi l'écran se transforme en interface braille ou en table tactile. Des boutons et détecteurs de mouvement sont disposés autour de la machine, la taille des caractères typographiques est revue à la hausse.(\)[*](img/blindInt) 
Il faut ainsi prévoir un accès aux informations, en dehors de toute mise en formes : dans le schéma qui suit, nous pouvons observer une séparation entre le [contenu et le contenant](img/separation) permettant une remanipulation de ce dernier. 
L'entreprise Indata a créé un [_patch_ ](img/zoomtext) permettant à l'utilisateur de faire lire n'importe quel texte présent à l'écran. Donnant ainsi accès aux informations présente sur le _web_ aux personnes à vision réduite. Parfois la machine vient remplacer une fonction perdue et rend la communication possible à des personnes lourdement handicapées. En 1986, Robert J. Cattoche présente, dans son livre _Computers for the Disabled_ , un système appelé [ACS][_Alternative Communication Système_ ]. Cette interface permet de transcoder du morse en langage via [un synthétiseur vocal.](img/handi)(\)
 
Enfin le système TACTOS élaboré au sein des laboratoires [Costech][centre de recherche de l'université technologique de compiègne], permet un report pixel par pixel des [informations présentent à l'écran](img/tactosEcran), sur des [cellules brailles](img/tactoscell) modifiées.L'utilisateur, aveugle, peut ainsi percevoir les éléments graphiques présents à l'écran. Pour ce faire il déplace son curseur (ou plutôt un ensemble de champ recepteur) rectangulaire et reçoit l'information sur son doigt posé sur l'interface braille. La forme du pointeur est donc adaptée à la forme du périphérique de sortie. De plus ce système n'admet que la présence de motif à fort contraste (voir totalement dans une logique binaire)  
Ce travail fait écho aux recherches effectuées par Bach-y-Ritta sur la substitution sensorielle chez les aveugles. Il souhaite démontrer , par son travail, en 1960, qu'il existe une plasticité cérébrale. Grâce à différents dispositif placés tantôt sur le ventre tantôt sur la langue, il permet aux aveugles de voir par le toucher.(\)

(\)Manuel De Landa, War in the Age of Intelligent Machines, ZoneBooks,1991, p. 226  
(\)Matthew Fuller, « Windows: a disorder riding machine », http://bak.spc.org/iod/Disorder.html, consulté en janvier 2015    
(\)<https://developer.apple.com/library/ios/documentation/UserExperience/Conceptual/MobileHIG/>
(\)Gnu, Libertés essentielles, <http://www.gnu.org/philosophy/free-sw.html>, consulté en janvier 2015  
(\)Frédéric Bordage, « Sobriété fonctionnelle : la clé de l’écoconception des logiciels ? », <http://www.greenit.fr/article/logiciels/sobriete-fonctionnelle-la-cle-de-l-ecoconception-des-logiciels-5101>, 21 février 2014   
(\)grennit.fr  
(\)Frédéric Bordage et Frédéric Lohier, « La clé de l’obsolescence programmée du matériel informatique », <http://www.greenit.fr/article/logiciels/logiciel-la-cle-de-l-obsolescence-programmee-du-materiel-informatique-2748>, 24 mai 2010    
(\)Anthony Masure ??  
(\)Dominique Archambault et Dominique Burger, « From Multimodality to Multimodalities : the need for independent models », 2001, consulté en janvier 2015  
(\)Christopher R. Murphy, « Computers and the Disabled », <http://courses.cs.vt.edu/cs3604/lib/Disabilities/murhpy.AT.html>, 1997, consulté en janvier 2015  
(\)Nolwenn Maudet, « Bach-y-Rita, voir par la langue », <http://strabic.fr/Bach-y-Rita>, février 2014, consulté en janvier 2015   

-------

Dans le livre intitulé _The Circle_ de Dave Eggers(\), Mae Holland obtient un job dans une entreprise technologique, à mesure qu'elle évolue au sein de l'entreprise le nombre de ses responsabilités augmentent et, corolairement, le nombre d'écrans sur son bureau aussi.
L'écran n'est plus qu'un terminal de commande et de consultation. La couche logicielle étant déportée vers le _cloud_. Les décors et la représentation des technologies dans le film _2001, l'Odyssey_ souligne aussi cette vision futuriste d'interface "située". Chaques fonctions du vaisseau et chaque activité de ces occupants sont figurées par [un nouvel écran](img/2001odyss). Le dévelopement du télé-travail et les nouvelles méthodes qui en découlent vont de plus en plus influencer le développement des interface pour faciliter et sécuriser la mobilité des employés.(\)

[ChromeOS](img/chromeos) utilise le principe de [_web app_][Une application web est une application fonctionnent dans un navigateur, utilisant des langages de développement web (type HTML, javascript)] et, dans sa forme première, supprime le multifenetrage. Ils sont par la suite revenu à un bureau plus classique avec le développement d'application hors-ligne(\). Windows 8, quant à lui, propose des applications fonctionnant [en plein écran](img/windows8). Le transport et le déplacement des éléments d'une fenêtre à l'autre est impossibles. Cette spécialisation des interfaces peut paraître perturbante, mais amène une nouvelle approche de nos outils.  
  
_Oblong enterprise_ est une compagnie américaine explorant le monde de l'interface et propose de nouvelles approches de ces dernières. 
Son créateur John Underkoffler est connu pour avoir produit les environnements systèmes et outils utilisés par les policiers de [_Minority Report_](img/minority). Il souligne dans une interview (\) que l'élément le plus important de ces films, n'est pas la reconnaissance gestuelle, mais la façon dont chaque écran est connecté l'un à l'autre, comment l'information peut transité d'une platforme à une autre. Après cette expérience cinématographique, il souhaite concrétiser son idée au travers de g-speak un espace 3D, dans lequel l'utilisateur est immergé dans ces données, navigant d'écrans en écran.
L'interface pensée par UnderKoffler s'inscrit dans une démarche initiée au tangible Media Group du MIT, au travers d'[Urp](img/urp), un programme d'architecture doté d'une interface tangible.(\)    

Nous pouvons penser à la création d'une interface plus diffuse, comme si nos objets allaient (sans pour autant devenir objet connecté) être interfacé, car subordonné par de micro-systèmes d'exploitation. Plus qu'une rupture totale avec le monde du bureau, un transfert pourrait s'opérer entre l'ordinateur et les objets qui y sont représentés. Durell Bishop, pense que les interfaces ne sont pas si évidente, que les boutons qui les composent et leurs design, son toujours au stade d'une interface textuelle. Ceux-ci ne serviraient simplement que d'un chemin vers un mot. Face à un objet mecanique l'homme peut se projeter des modèles mentaux, élaborant le fonctionnement du système. Ce qui est plus difficile dans le cas d'une interface graphique, plus lisse. En 1977, James Jerome Gibson, psycologue américain, attribut le terme d'affordance, comme étant l'ensemble des possibilités d'actions, dans l'environnement, d'un objet en fonction des caractéristiques de l'objet et de l'acteur/observateur.   
Afin d'étendre le champ d'action de l'ordinateur, limité à l'écran, Bishop y connecte des [« objet signaux »][Heinz Werner] de la vie quotidienne, y ajoutant ainsi une troisième dimmension. Au travers de ces installations [expérimentales](img/durell), il souhaite libéré l'ordinateur de son confinement et le rendre ubiquitaire. Citant Mark Weiser, ingénieur au xerox parc, il avance l'éventualité de la disparition totale de l'ordinateur, ou plutot de l'ordinateur tel que nous l'utilisons aujourd'hui. Il parle de son devenir  transparent.(\)
Dans la ligné du designer [Dieter Rams][Designer fonctinaliste allemand, ayant principalement travaillé pour les produits Braun dans les années 60.] Mark Weiser a défini 4 notions de ce qui lui semble être le devenir de l'informatique : 

* Le but des ordinateurs est d'aider les gens à faire autres choses
* Il est notre humble et silencieux serviteur
* L'ordinateur doit étendre notre inconscient
* La technologie doit créer du calme

Il est parfois difficile d'envisager un monde sans métaphore, sans bureau augmenté. Dans le film __Her__ de Spike Jonze que nous avons analysé auparavant. L'accès oral aux ordinateurs est certes innovant, mais nous pouvons noter des réminiscences des anciens idiomes, la personne cite parfois une action liée à un bouton, [une entrée graphique.](img/herlettre)   
Néanmoins l'artiste et ingénieur Brendan Howell(\) rêve d'un monde sans écran. Il associe l'interface graphique à un modèle économique capititaliste loin des utopies premières de l'informatique. Il prend pour exemple, la place qu'occupe l'image dans l'interface de la web app [YouTube](img/brendan1). Il souligne le fait que 50% de son interface nous pousse à la consommation. De la même manière, nous voyons sur ce schéma que dans la composition même du [processeur](img/brendan2), 80% de sa puissance de calcul est consacrée à l'affichage des données que nous manipulons.  
Dans son projet _Screnless Office_, il souhaite proposer sa propre vision du bureau augmenté, qui se libérerait du joug de l'écran et des éléments graphiques qui y sont associés. L'ordinateur serait toujours présent, sous-jacent à nos outils, mais l'ensemble de sa puissance ne serait plus consacré aux performances graphiques, mais au soutient de nos propres actions, au stockage d'informations ou encore à la communication.   
Cette démarche est encore au stade purement théorique et il ne l'a concrétisée qu’au travers de quelques dispositifs. La machine à [twitter](img/brendan3) se focalise sur l'information envoyé / partagé. Chaque _Twitt_ est imprimé sur un rouleau de papier d'une caisse enregistreuse. Excluant tout écran le message ne subit plus la pollution visuel  induit par l'interface du site. Il va sans dire que ce projet reprend à la lettre le dispositif [memex](img/brendan4) imaginé par Vannevar Bush. 

Par oposition la réalité augmenté ne supprime pas l'écran mais l'hybride à notre vision. Les _google glass_ diminuent la distance entre l'individu, la machine et son interface graphique. Elle agit telle une [surcouche](img/glass4) sur le monde physique. Celui-ci est annoté, calculé et quantifié. Ces systèmes insérent des éléments virtuels dans un espace réel. 
Le projet Gravity (\) dévellope un système de CAO dans [un espace augmenté](img/gravity). Une équipe du laboratoirz _Innovation design et Ingénierie_ de la _Royal College of Art _ a réalisé fin 2013 un prototype de tablette permettant de déssiner un model 3D et de le spatialiser. Grâce à des lunettes et d'un stylet, l'utilsateur peut prototyper des models parfaitement réutilisable dans n'importe quel logiciel. Ce projet fait écho au programme _Sketchpad_ de Ivan Sutherland, lui même ayant inventé un des premiers systèmes de [réalité augmenté]().

Le rapprochement des ordinateurs aux êtres humains, nous pousse à envisager une hybridation totale du corps à l'objet électronique. 
En 1970 à l'université de UCLA, une équipe de chercheur subventionné par la DARPA(\), a élaboré la première interface neuronale directe permettant à un singe de manipuler un bras électronique via un casque capturant l'activité de son [cerveau](). Il est difficile d'imaginer quelles formes prendrons les nouvelles interfaces, il y aura-t-il une interface graphique présente dans notre cerveau, ou les nouvelles interactions seront libérées de toute représentions. Du moins ces expérimentations ont attisé l'imagination de nombreux cinéastes, pourrions nous, nous connecter directement au web via un port cranien et télécharger du contenu directement dans notre cerveau tel Johnny Mnemonic(\) ou enregistrer les flux du cortex cérébral pour partager des sensations et des experiences, à l'identique, entre individu (\). 


(\)Dave Eggers, _The Circle_, McSweeney's, Octobre 2013  
(\)Nick Hardiman, « 10 good reasons why working remotely makes sense », <http://www.techrepublic.com/blog/10-things/10-good-reasons-why-working-remotely-makes-sense/#ftag=RSS56d97e7>, janvier 2015  
(\)<https://en.wikipedia.org/wiki/Chrome_OS>  
(\)_Oblong Industries: Our Story_, <http://vimeo.com/97753856>, 2014,consulté en janvier 2015  
(\)Bill Moggridge, _Designing Interactions_, p. ??, The MIT press, 2006  
(\) _ibid_, p.541
(\)Brendan Howell, _The Screenless Office_ ,<http://www.wintermute.org/brendan/?e=261>, 2014  
(\)« Gravity 3D augmented-reality sketchpad », <http://www.electronicproducts.com/Software/Development_Tools_and_Software/Gravity_3D_augmented_reality_sketchpad.aspx>, 2014   
(\)<https://en.wikipedia.org/wiki/Brain_computer_interface>  
(\)Robert Longo, _Johnny Mnemonic_, 1995  
(\)Kathryn Bigelow, _ Strange Days_, 1995
