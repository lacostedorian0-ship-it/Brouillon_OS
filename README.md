# BROUILLON : ta calculatrice est ton cahier de brouillon, et il est vivant

**BROUILLON remplace l'écran d'accueil de la calculatrice NumWorks (n0120)
par une page de cahier de brouillon.** Papier à grands carreaux, marge rouge,
trous de classeur (on voit le bureau à travers), tache de café. Tout est
dessiné au stylo bille, et les traits **tremblent** comme dans un dessin
animé fait main. Les applis sont des **gribouillis**, les jeux sont des
**autocollants** scotchés de travers, et **Kevin**, un bonhomme bâton, vit
sur la page : il saute de dessin en dessin, s'ennuie, fait des pompes,
dessine dans tes marges, te parle… et **plonge dans les applis avant toi**.
Quand tu reviens, l'appli lui a fait quelque chose.

![BROUILLON](docs/apercu.png)

<p align="center"><img src="docs/nav.gif" alt="Kevin saute de dessin en dessin et tourne la page" width="480"></p>

## Ce que fait BROUILLON

- **Un cahier dessiné à la main, en direct.** Rien n'est une image : chaque
  trait est tracé par le code à chaque image, avec une main qui tremble
  (les traits « bouillonnent » plusieurs fois par seconde). L'écriture aussi
  est faite à la main : chaque lettre est un peu à côté de sa ligne.
- **Les applis sont des gribouillis** qui bougent quand tu les choisis : la
  courbe du Grapheur ondule, le serpent de Python se tortille, l'atome de
  Chimie tourne, l'engrenage des Paramètres aussi, la balance d'Inférence
  hésite, les barres des Statistiques montent et descendent. Le dessin
  choisi est **entouré au stylo** (le cercle se trace devant toi) et son nom
  est **surligné au fluo**.
- **Les jeux `.nwa` sont des autocollants** avec leur vraie icône, collés de
  travers avec du scotch, sur la page « Mes jeux ».
- **Kevin tourne les pages.** Au bord de la page, la page se tourne (avec son
  ombre et son dos) et Kevin, accroché au coin, est emporté avec.
- **OK : Kevin plonge dans l'appli**, la tête la première, et l'encre bleue
  inonde l'écran. L'appli s'ouvre.
- **Quand tu reviens, il ressort… avec les conséquences :**

  | Il sort de… | Et alors… |
  | --- | --- |
  | Python | **un vrai serpent le poursuit** à travers la page |
  | Grapheur | il **surfe sur une sinusoïde** (« WOUHOU ! sin(x) ! ») |
  | Paramètres | quelqu'un a réglé la gravité : il **marche la tête en bas** |
  | Chimie | **BOUM**. Noir de suie, cheveux dressés (« Na + H2O. Ne faites pas ça chez vous. ») |
  | Suites | il se **divise en clones** de plus en plus petits (u(n+1) = 0,72 u(n)) |
  | Inférence | un **tampon géant H0 REJETÉE** l'écrase |
  | Probabilités | il sort **en roulant dans un dé** |
  | Finance | **pluie de pièces**, haut-de-forme et monocle (« Je suis riche. 2 centimes. ») |
  | Statistiques | les **barres de l'histogramme** le font monter et descendre |
  | Équations | il n'a **pas trouvé x** (il l'a sur la tête) |
  | Régressions | il glisse le long de **la droite de régression** |
  | Calculs | il brandit **ton dernier résultat** sur une pancarte |
  | un jeu | **casque sur les oreilles, yeux carrés** : « Encore une partie. Une seule. » |

- **Le prof corrige tes calculs au stylo rouge.** Fais des calculs dans
  Calculs, reviens : « **Contrôle surprise** ». Tes calculs s'écrivent sur la
  copie, puis le stylo rouge passe : coches, croix, commentaires, et une
  **note sur 20** entourée.

  | Tu calcules… | Le prof écrit… |
  | --- | --- |
  | `6×7` → 42 | « Bonne réponse. Mais quelle question ? » (et 20/20 pour la référence) |
  | `1+1` | « Sérieux ? La calculatrice pour ça ? » |
  | `6×111` → 666 | « Voir moi après le cours. » |
  | `1/0` | « Division par 0 : une heure de colle. » |
  | un nombre premier | « Premier. Seul, comme toi le samedi. » |
  | un carré parfait | « Carré parfait. Comme ta coupe ? » |
  | π | « π n'est pas un dessert. Quoique. » |
  | un nombre énorme | « Ton nombre déborde de la marge. » |

  Et `0`, `69`, `404`, `1337`, `2026`, les négatifs, les nombres à virgule…
- **Le bouton panique.** La touche **Effacer** froisse la page en boule et
  ouvre **Calculs**. Le prof arrive ? Tu calcules, évidemment. Quand tu
  reviens, la page est défroissée et Kevin souffle : « Il est parti ? On a eu
  chaud. »
- **Kevin a sa vie.** Si tu ne fais rien, il s'assoit au bord du dessin en
  balançant les jambes, fait des pompes (« Je compte en binaire »), danse,
  lit le manuel, te parle (« Mon père était un trait. Ma mère, un rond. »),
  **gribouille dans tes marges** (cœurs, étoiles, fleurs, cubes, le fameux
  « S » que tout le monde dessine, « Kevin était là »…), et finit par
  **s'endormir** (des Z sortent, la LED respire en bleu).
- **Tu peux l'embêter.** **x,n,t** le chatouille (il tombe, des étoiles, il
  râle), **Var** le **gomme** (une gomme le frotte jusqu'à ce qu'il
  disparaisse, puis il se **redessine** lui-même au crayon, vexé), **Ans** le
  fait danser.
- **La trousse** (Boîte à outils) : neuf trucs à faire en cours, voir plus
  bas.
- **La batterie est un crayon** qui raccourcit, la **luminosité** est « le
  néon de la classe », et la barre de titre des applis devient **bleu stylo
  bille**.
- **Installateurs en un clic pour Mac et pour Windows** : une page web locale
  (au look cahier, elle aussi) qui détecte la calculatrice, gère tes jeux et
  installe tout avec un bouton. Sur Windows, un simple `.exe` : ni Python ni
  pilote à installer.

<p align="center"><img src="docs/python.gif" alt="Kevin sort de Python, poursuivi par un serpent" width="480"></p>

## La trousse

Ouvre-la avec la touche **Boîte à outils**.

| Outil | Ce que ça fait |
| --- | --- |
| **Cocotte** | la **cocotte en papier**, celle de la cour de récré : choisis une couleur, elle s'ouvre et se ferme en épelant (R-O-U-G-E), choisis un nombre, elle compte, choisis le dernier : le rabat se soulève et ton avenir est écrit dessous (« Ton crush a exactement la même calculatrice que toi. ») |
| **Masque** | mets la calculatrice **devant ta bouche** et parle en gardant une touche appuyée : la bouche s'ouvre avec toi. Les flèches font bouger les yeux, les chiffres changent le visage : moustache, lunettes, **vampire** (la LED devient rouge quand il parle), clown, cyclope, **robot** (LED cyan), monosourcil, sans dents, Kevin |
| **Écran HS** | **la farce** : donne la calculatrice à ton voisin. Quelques secondes plus tard, **l'écran se fissure** depuis un point d'impact, les cristaux liquides coulent en noir, des colonnes de pixels meurent, et chaque touche qu'il appuie fait empirer les choses. **Retour trois fois** : « Réparé ! (C'était une blague. Respire.) » |
| **Duel** | **western à deux joueurs** : touche **0** à gauche, touche **EXE** à droite. Au « **PAN !** », le premier qui tire gagne (temps de réaction en ms). Mais attention aux pièges : « PAN… CAKE ! », « PAN… DA ! », « PAN… TALON ! » : tirer avant, c'est perdre. Premier à 3 |
| **Punitions** | choisis ta punition (« Je ne dois pas appeler le prof maman. »), **Kevin l'écrit 100 fois** à ta place, de plus en plus vite et de plus en plus mal, en se plaignant, jusqu'à l'épuisement |
| **Dessin** | dessine avec les flèches (OK lève le stylo, Var : la gomme, 0 : tout effacer). **Kevin marche sur tes traits** : il monte les marches, tombe dans le vide, fait demi-tour contre les murs, proteste si tu l'enfermes ou si tu dessines sur lui |
| **Avion** | un avion en papier entre les crayons et les règles : garde une touche appuyée pour monter |
| **Morpion** | contre Kevin. **Il triche** : quand tu vas gagner, sa gomme « glisse » sur une de tes croix. Et si tu gagnes quand même… **il retourne la table** |
| **Réglages** | LED oui/non, Kevin bavard oui/non, gommer ses graffitis, et les statistiques (applis ouvertes, paniques, chatouilles, gommages, record de l'avion, tables retournées) |

<p align="center"><img src="docs/copie.gif" alt="Le prof corrige tes calculs au stylo rouge" width="480"></p>

## Les commandes

| Touche | Action |
| --- | --- |
| ◀ ▶ ▲ ▼ | passer d'un dessin à l'autre ; au bord, tourner la page |
| 1 à 9 | aller à la page 1, 2, 3… |
| OK | ouvrir l'appli (Kevin plonge dedans) |
| Boîte à outils | la trousse |
| **Effacer** | **BOUTON PANIQUE** : la page se froisse, Calculs s'ouvre |
| Retour | revenir à la première page |
| x,n,t | chatouiller Kevin |
| Var | gommer Kevin |
| Ans | Kevin danse |
| 0 | Kevin commente le dessin choisi |
| + − | la luminosité (le néon de la classe) |

## Captures

| | |
| --- | --- |
| ![Page 1](docs/page1.png) | ![Kevin parle](docs/kevin_parle.png) |
| La première page | Kevin te parle |
| ![Page qui tourne](docs/tourne_page.png) | ![Encre](docs/encre.png) |
| Kevin tourne la page | L'encre inonde l'écran : l'appli s'ouvre |
| ![Grapheur](docs/gag_grapheur.png) | ![Paramètres](docs/gag_reglages.png) |
| De retour du Grapheur | De retour des Paramètres |
| ![Chimie](docs/gag_chimie.png) | ![Suites](docs/gag_suites.png) |
| De retour de Chimie | De retour des Suites |
| ![Inférence](docs/gag_inference.png) | ![Finance](docs/gag_finance.png) |
| De retour d'Inférence | De retour de Finance |
| ![Probabilités](docs/gag_probas.png) | ![Régressions](docs/gag_regression.png) |
| De retour des Probabilités | De retour des Régressions |
| ![Calculs](docs/gag_calcul.png) | ![Copie](docs/copie.png) |
| De retour de Calculs | La copie corrigée |
| ![Panique](docs/panique.png) | ![Gomme](docs/gomme.png) |
| Le bouton panique | Var : la gomme |
| ![Assis](docs/assis.png) | ![Chatouille](docs/chatouille.png) |
| Kevin s'ennuie | x,n,t : la chatouille |
| ![Trousse](docs/trousse.png) | ![Réglages](docs/reglages.png) |
| La trousse | Les réglages |
| ![Cocotte](docs/cocotte.png) | ![Cocotte](docs/cocotte_nombres.png) |
| La cocotte | Choisis un nombre |
| ![Cocotte](docs/cocotte_avenir.png) | ![Masque](docs/masque_moustache.png) |
| Ton avenir | Le masque (moustache) |
| ![Vampire](docs/masque_vampire.png) | ![Robot](docs/masque_robot.png) |
| Vampire | Robot |
| ![Avant](docs/fissure_avant.png) | ![Fissure](docs/fissure.png) |
| La farce est prête… | …l'écran se fissure |
| ![Pire](docs/fissure_pire.png) | ![Réparé](docs/fissure_reparee.png) |
| Il a touché une touche | Retour x3 : réparé |
| ![Duel](docs/duel_pancake.png) | ![Duel](docs/duel_gagne.png) |
| PAN… CAKE ! (ne tire pas) | J2 gagne en 360 ms |
| ![Punition](docs/punition.png) | ![Punition](docs/punition_finie.png) |
| Kevin copie tes lignes | 100/100 |
| ![Dessin](docs/dessin.png) | ![Avion](docs/avion.png) |
| Kevin marche sur ton dessin | L'avion en papier |
| ![Morpion](docs/morpion.png) | ![Table](docs/morpion_table.png) |
| Le morpion | Kevin retourne la table |

<p align="center"><img src="docs/dessin.gif" alt="Kevin marche sur un dessin" width="400"> <img src="docs/boot.gif" alt="La couverture du cahier s'ouvre" width="400"></p>

> Les captures viennent du simulateur, qui ne sait pas charger de jeux : la
> page « Mes jeux » y est vide. Sur la calculatrice, chaque jeu y est un
> autocollant avec son icône.

## Installation

### 1. Obtenir BROUILLON

Depuis juillet 2021, le code d'Epsilon (le logiciel de la NumWorks) n'est plus
sous licence libre. BROUILLON ne publie donc **aucun code ni aucun firmware de
NumWorks** : seulement un **patch** (`patches/brouillon-epsilon.patch`) et son
propre code. Le firmware se compile à partir des sources officielles de
NumWorks, dans ton compte GitHub ou sur ton Mac.

**Sans rien compiler (Mac ou Windows)**

1. En haut de cette page : **Use this template** > **Create a new repository**,
   coche **Private** (obligatoire : la compilation refuse de tourner dans un
   dépôt public, pour que le firmware ne soit pas téléchargeable par tous).
2. Facultatif : ajoute tes jeux `.nwa` dans le dossier `games/` de ta copie
   privée (*Add file* > *Upload files*). Ils seront préparés et inclus dans
   l'installateur, et deviendront des autocollants.
3. Dans ta copie : onglet **Actions** > **Build BROUILLON** > **Run workflow**.
4. Environ 15 minutes plus tard, en bas de la page de la compilation,
   télécharge **BROUILLON-Mac** ou **BROUILLON-Windows** et décompresse-le
   (deux fois pour la version Mac : GitHub met le zip dans un zip).

**En compilant sur ton Mac**

```bash
brew install make dfu-util libusb
brew install --cask gcc-arm-embedded
git clone https://github.com/derim00/brouillon.git && cd brouillon
./scripts/build-firmware.sh
```

Le script télécharge Epsilon au commit indiqué dans `EPSILON_COMMIT`
(Epsilon 26.1, la dernière version publiée par NumWorks), applique le patch,
compile, prépare les jeux de `games/` et remplit le dossier `installer/`.

### 2. Installer sur la calculatrice

**Sur Mac**

1. Une seule fois : `brew install libusb dfu-util` (et
   `brew install --cask gcc-arm-embedded` pour ajouter d'autres jeux).
2. Double-clique sur **`Installer BROUILLON.command`** (la première fois :
   clic droit > **Ouvrir**). La page de l'installateur s'ouvre
   (http://127.0.0.1:8771).

**Sur Windows** (rien à installer : ni Python, ni pilote)

1. Décompresse **BROUILLON-Windows** (clic droit > *Extraire tout*) : ne
   lance pas l'installateur depuis l'intérieur du zip.
2. Dans le dossier `BROUILLON`, double-clique sur **`Installer BROUILLON.exe`**
   (si SmartScreen s'affiche : *Informations complémentaires* > *Exécuter
   quand même*). Une fenêtre noire s'ouvre avec la page de l'installateur dans
   ton navigateur : laisse-la ouverte, et ferme-la à la fin pour quitter.

**Ensuite, sur les deux**

3. Branche la calculatrice en USB et appuie sur **Reset** au dos : elle
   redémarre sur le système officiel.
4. Quand le voyant passe au vert, glisse tes jeux `.nwa` dans la page si tu
   veux, puis clique sur **Installer BROUILLON**.

L'installateur vérifie que le **slot B** est libre avant d'écrire : le système
officiel (slot A) n'est jamais modifié. Il prépare les jeux pour leur place
dans le slot B (comme le fait le site de NumWorks), les copie, les relit pour
les vérifier, puis installe BROUILLON et le démarre.

## À savoir

- **Calculatrice** : NumWorks **n0120**, avec le logiciel officiel
  **26.4.0** dans le slot A. BROUILLON est compilé à partir d'Epsilon 26.1
  (la dernière version publiée) avec le numéro de version 26.4.0.
- **Mémoire** : le cahier (la page, Kevin, ses graffitis, ton dessin, tes
  records) reste en mémoire quand tu ouvres une appli. Il repart de zéro
  après un Reset.
- **La copie** : seuls les résultats calculés depuis le dernier démarrage
  sont corrigés, et seulement les 6 derniers.
- **LED et luminosité** : BROUILLON ne touche à la LED que sur son écran
  (Kevin qui dort, l'encre, la copie, le masque, le duel, la farce) ; elle
  redevient normale dès que tu ouvres une appli. Tu peux la couper dans
  Trousse > Réglages. En mode examen, il n'y touche jamais.
- **Batterie** : le cahier est animé en continu, comme un dessin animé.
- **Après un Reset**, la calculatrice revient sur le système officiel :
  BROUILLON reste dans le slot B, il suffit de relancer l'installation.
- **Un seul système dans le slot B** : BROUILLON remplace
  [NUM TV](https://github.com/derim00/numtv),
  [GLOUTON](https://github.com/derim00/glouton),
  [NUMVERSE](https://github.com/derim00/numverse),
  [PSP-OS](https://github.com/derim00/psp-os),
  [Switch-OS](https://github.com/derim00/switch-os) ou
  [Windows-OS](https://github.com/derim00/windows-os) s'il était installé,
  et inversement. Les installateurs peuvent tourner en même temps (ports 8765
  à 8771).
- **Touches Home et On/Off** : sur un logiciel non officiel, le système de la
  calculatrice gère lui-même ces deux touches. BROUILLON efface au démarrage
  le point de retour laissé par le système officiel pour que Home ramène au
  cahier ; si la calculatrice revient quand même sur le slot A, utilise
  **Retour** (↩) pour revenir à BROUILLON depuis une appli.
- **Mode examen** : BROUILLON garde les règles du mode examen d'Epsilon
  (applis interdites, jeux bloqués : les autocollants sont confisqués).
- **La farce de l'écran cassé** est une blague entre amis : rien n'est cassé,
  Retour trois fois remet tout en ordre.
- **Jeux** : seulement des applis `.nwa` dont tu as le droit de te servir, et
  uniquement dans ta copie privée : jamais dans ce dépôt public.

## Comment c'est fait

| Fichier | Rôle |
| --- | --- |
| `patches/brouillon-epsilon.patch` | BROUILLON (`apps/home/doodle`), le branchement des résultats de Calculs, l'animation continue (`escher`), la barre bleu stylo des applis, le correctif Home / On-Off |
| `apps/home/doodle/shell.cpp` (dans le patch) | le cahier : papier Seyès, pages, sélection au stylo et au fluo, pages qui tournent, couverture, inondation d'encre, page froissée (bouton panique), stylo rouge du prof, post-it, bulles, LED, luminosité |
| `apps/home/doodle/kevin.cpp` (dans le patch) | Kevin : un squelette de 11 traits posé par des angles, ses poses, sa vie (sauts, ennui, sommeil, graffitis), la chatouille, la gomme, et les 13 retours d'appli |
| `apps/home/doodle/doodles.cpp` (dans le patch) | le gribouillis de chaque appli, tracé au stylo |
| `apps/home/doodle/trousse.cpp` (dans le patch) | la trousse et ses 9 outils (cocotte, masque, écran HS, duel, punitions, dessin avec la physique de Kevin, avion, morpion tricheur, réglages) |
| `apps/home/doodle/gfx.cpp` (dans le patch) | le dessin par bandes de 12 lignes : traits lissés, traits « à la main » qui tremblent, cercles au stylo, taches d'encre, hachures, écriture manuscrite, autocollants tournés |
| `apps/home/doodle/food.cpp` (dans le patch) | les derniers résultats de l'appli Calculs, que le prof corrige |
| `scripts/build-firmware.sh` | télécharge Epsilon, applique le patch, compile, prépare l'installateur |
| `scripts/photos.py` | transforme la séance photo du simulateur en images de ce README |
| `installer/server.py` | serveur local (127.0.0.1 uniquement) de l'installateur, Mac et Windows |
| `installer/dfu_launch.py` | lance l'outil DFU de NumWorks avec libusb (Homebrew ou `libusb-package`) |
| `installer/link_games.py` | prépare les jeux `.nwa` pour leur adresse dans le slot B |
| `scripts/build-windows-installer.py` | fabrique l'installateur Windows (`.exe`, PyInstaller) |
| `.github/workflows/build.yml` | la compilation dans ta copie privée |

## Licence

Code de BROUILLON (le patch, les scripts, l'installateur) : CC BY-NC-SA 4.0,
voir [LICENSE](LICENSE). Epsilon appartient à NumWorks et n'est pas inclus.
BROUILLON est un projet de fan, non affilié à NumWorks.
