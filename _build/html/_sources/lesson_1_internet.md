# Leçon 1 -- Internet : une innovation sociotechnique


- Répondre à 3 questions sur Wooclap en cliquant [ici](https://app.wooclap.com/TCDRGN?from=event-page) ou en flashant le QR code ci-dessous

![](./images/qr_code_wooclap_culture_numerique.png)



## Une brève chronologie du numérique

<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1ZgnK7tp0L8hBm3_MwlHLURJoUwD0Ro7ydz3KyVyDHmM&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

[La timeline en grand format](https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1ZgnK7tp0L8hBm3_MwlHLURJoUwD0Ro7ydz3KyVyDHmM&font=Default&lang=en&initial_zoom=2&height=650)


__Exercices__ :

- Parcourir la timeline

- Répondre à deux nouvelles questions sur Wooclap en cliquant [ici](https://app.wooclap.com/RQTZAO?from=event-page) ou en flashant le QR code ci-dessous :

![](./images/qr_code_wooclap_debut_numerique.png)

<!-- La timeline montre que le numérique est une histoire scientifique et technique, mais aussi une histoire politique à travers les institutions mises en place pour développer Internet et réguler le réseau, une histoire culturelle à travers les pratiques des outils numériques, leurs inscriptions dans des oeuvres littéraires (Azimov), cinématographiques, une histoire des transformations sociales (le télétravail, les sites de rencontre, les réseaux sociaux) -->



## La commutation par paquet et le protocole TCP/IP


```{note}
Les informations techniques contenues dans cette partie sont issues du très bon sites https://www.infoforall.fr/act/snt/cat/internet/
```


Internet est le nom donné au protocole permettant à des ordinateurs de communiquer à distance, c'est-à-dire de s'échanger des informations. Ce protocole est le __TCP/IP__, qui signifie "Transmission Control Protocol/__Internet__ Protocol". Il a été mis au point en __1973__ par Vinton Cerf et Robert Kahn dans le cadre du projet __ARPANET__ initié en __1966__ sous l'égide de l'Information Processing Techniques Office (IPTO). L'IPTO est lui-même une subdivision de l'Advanced Research Projetcs Agency. L'ARPA est une agence mise en place en 1958 par le Département américain de la Défense en réponse à l'envoi du premier satellite Spoutnik par l'Union soviétique.

La première démonstration d'une communication en réseau entre deux ordinateurs a eu lieu le 9 décembre 1968 avec en vedette Doug Engelbart. Alors qu'Engelbart et son équipe étaient dans le San Francisco’s Civic Auditorium, ils ont réussi à interagir avec un autre ordinateur situé dans leur laboratoire de l'université de Stanford. C'est aussi la première fois qu'on a utilisé une souris. Efin, cette démonstration est considérée comme "the mother of all demos".

<iframe width="560" height="315" src="https://www.youtube.com/embed/yJDv-zdhzMY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Un an après la démonstration, ARPANET permit de connecter les ordinateurs de la UCLA’s School of Engineering (Los Angeles) à ceux de la  (Menlo Park), de l'UC Santa Barbara et de l'université de l'Utah. En 1971, 23 organisations réparties sur les côtes est et ouest des USA étaient connectées à l'ARPANET, et en 1973 Londres rejoignait le réseau.


![](./images/ARPANET-Sistema.gif)

![](./images/arpanet_sept1973_large.png)

Au départ, l'ARPANET fonctionne grâce au protocole NPC (Network Protocol Program). Ce protocole pose toutefois 2 problèmes:

- La communication passe uniquement par les câbles téléphoniques, ce qui réduit son application militaire puisqu'il ne permet pas d'échanger des informations par radio ou satellite {cite:p}`abbateInventingInternet1999`.

- Il faut appartenir au même réseau. Ce qui rend plus difficile son usage académique par exemple.

Deux problèmes que le protocole TCP/IP (donc Internet) va permettre de résoudre. Dans les deux cas, les protocoles NCP (Arpanet) et TCP/IP (Internet) mettent en application le concept "switching packet" (communication par paquet) proposé par Paul Baran (Rand Company) et Donald Davies (National Physical Laboratory). Pour schématiser, on parle de "paquet", car l'information est envoyée comme on le fait pour une lettre ou un colis : en plus du message, chaque "paquet d'information" possède une "en-tête" précisant l'adresse de l'émetteur et du destinataire.
Ce sont les fameuses __adresses IP__.

Si l'__IP__ peut être assimilé à une adresse, le __TCP__ est une sorte d'accusé de réception permettant aux deux machines communiquant entre-elles de savoir si la communication est "fiable" :

- à la machine émettrice de savoir que le paquet est bien arrivé

- à la machine réceptrice de savoir si le paquet reçu comporte de erreurs sur certains bits

- à la machine émettrice d'émettre à nouveau un paquet si besoin

Le protocole __TCP__ permet également de subdiviser un message en plusieurs paquets et d'envoyer plusieurs messages en même temps (ou lancer plusieurs programme en même temps : lancer une vidéo et lire les mails en même temps)


![](./images/switching_packets.png)

L'intérêt de la commutation par paquet est qu'il n'est plus nécessaire de disposer d'un "noeud central" qui sait tout, comme cela était le cas avec les réseaux téléphoniques. Grâce aux informations contenues dans l'IP, chaque noeud (routeur) sait ce qu'il doit faire du paquet reçu : le garder pour lui, le transmettre à une autre machine de son réseau ou l'envoyer à un autre noeud (routeur). Outre l'innovation technique qu'elle représentent, la mise au point de la communication par paque a des implications économiques, politiques et sociales.

En effet, dans la mesure où le protocole TCP/IP permet de passer d'un réseau centralisé à un réseau distribué et, surtout, de connecter différents réseaux entre-eux, elle remet en question (en partie) le monopole que les compagnies des téléphones pouvaient avoir sur les réseaux de télécommunications et des bénéfices économiques qui pouvaient en résulter. Pour les mêmes raisons, il est plus difficile pour un État de contrôler les informations qui circulent dans un réseau distribué. Enfin, le "savoir" est distribué entre tous les noeuds (donc les utilisateurs) du réseau. De cette façon chaque noeud est capable d'apporter des changements aux systèmes d'information et de les diffuser au sein du réseau sans avoir à passer par un opérateur central qui pourrait bloquer l'information {cite:p}`cardonCultureNumerique2019`.

![](./images/paul_baran_network.png)

Toutefois, il faut bien comprendre que les concepts qui sont au fondement d'Internet émergent dans des communautés déjà familiarisées à l'idée que le savoir peut et doit être partagé horizontalement. Par exemple, Steward Brand, figure de la mouvance hippie à San Francisco et proche d'Engelbart, va être à l'origine du _World Earth Catalog_, sorte de Wikipedia papier avant l'heure dans lequel n'importe qui peut publier ses trucs et astuces (une recette de cuisine, un mode d'emploi pour construire son ordinateur, etc.). On retrouve ainsi l'idée d'un savoir distribué et accessible de n'importe quel endroit du réseau. Une idée que les belges Paul Otlet et Henri Lafontaine avaient déjà essayé de concrétiser à travers la construction du Mundaneum, sorte de bibliothèque universelle. Paul Otlet imagine également une machine connectée, la Mondothèque, "dans l'idée de créer un réseau international des savoirs" {cite:p}`cardonCultureNumerique2019{p. 84}`.

![](./images/whole_earth_catalog.jpeg)

```{margin}
Le "communalisme" est une des quatre normes constituant l'ethos scientifique selon Robert Merton {cite:t}`mertonSociologyScienceTheoretical1973`. Le communalisme implique que les connaissances produites sont des biens communs de la communauté scientifique et doivent pouvoir circuler librement entre les membres de cette commmunauté. La "qualité" de ces biens communs est en partie assuré par le "scepticisme organisé", c'est-à-dire un examen critique des résultats issus de la recherche.
```

On peut également faire l'hypothèse que la commutation par paquet, telle que conceptualisée par Paul Baran et Donald Davies et implémentée dans la norme TCP/IP, a pu s'imposer comme le "système" de communication en réseau, car elle s'est développée au sein de communautés épistémiques qui se vivaient déjà en réseau international et travaillant selon le principe du "communalisme". Par exemple, les informaticien.nes travaillaient à partir de programmes libres développés dans le cadre d'un "scepticisme organisé" comme l'illustrent les "Request For Comment" (RFC) qui ont accompagné le développement d'Internet. Les RFC sont des documents dans lesquelles les informaticien.nes présentent et mettent en discussion les résultats de leur recherches. Le premier RFC est publié en 1969 par Steve Crocker (UCLA). Il décrit le fonctionnement du premier protocole de l'ARPA Network {cite:p}`crockerHostSoftware1969`. Le RFC 1122, qui fixe définitivement le protocole TCP/IP comme la norme internet, est publié en 1983(voir https://www.rfc-editor.org/rfc/rfc1122). Aujourd'hui encore, de nouveaux RFC continuent d'être publiés. Ainsi, en 2022, la norme TCP/IP a fait l'objet d'un nouvel RFC.


Outre que le principe d'un réseau de télécommunication distribué résonne avec les pratiques des communautés épistémiques engagées dans le développement d'Internet, son "succès" tient probablement au fait qu'elle a apporté une solution "peu coûteuse" aux problèmes pratiques que rencontrent les chercheurs et chercheuses à l'heure où se développaient de grands équipements, notamment les grands ordinateurs. En effet, avant la création de réseau d'échange de données entre ordinateur, les scientifiques devaient se déplacer physiquement. Avec Internet et la norme TCP/IP, non seulement on peut envoyer plusieurs requêtes en "même temps" à un ordinateur distant de plusieurs milliers de kilomètres, mais il n'est plus nécessaire de faire partie du même "réseau informatique".


Enfin, Internet et les protocoles qui sont derrières constituent des innovations sociotechniques dans la mesure où elles conduisent à la création de nouvelles institutions dont le rôle va être de réguler le trafic sur les réseaux, gérer les adresses IP, organiser les modifications des protocoles :

- l'IETF (Internet Engineering Task Force) : elle s'occupe des couches basses de l'infrastructure et du réseau. C'est elle qui gère aujourd'hui les RFC

- l'ICANN (Internet Corporation for Assign Names and Numbers) gère les adressages IP et les noms de domaines comme les terminaisons .fr, .com, .org, etc.

- la W3C (World Wide Web Consortion) traite des couches hautes du web comme la spécification du langage HTML. Elle a mis en place des procédures ouvertes et les décisions se prennent par consensus.


## Le Web

Internet, a proprement parlé, correspond à l'infrastructure réseau qui permet aux ordinateurs de communiquer entre eux. Le partage d'information nécessite d'utiliser d'autres applications comme les e-mails. Le Web en est une autre. Il repose sur le protocole __http__ mis au point en 1989 par Tim Berners-Lee et le mathématicien belge Robert Cailliau. Il consiste à attribuer à chaque document partagé sur le réseau une URL (uniform resource locator) permettant de passer d'un document à un autre. Le Web repose sur deux autres "technologies" : le lien hypertexte et leangage html (hypertext markup langage). Le Web correspond finalement à l'ensemble des documents hypertextes auxquels on peut accéder avec un navigateur Web.
