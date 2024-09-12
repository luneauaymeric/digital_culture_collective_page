# Une brève chronologie du numérique


<iframe src='https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1ZgnK7tp0L8hBm3_MwlHLURJoUwD0Ro7ydz3KyVyDHmM&font=Default&lang=en&initial_zoom=2&height=650' width='100%' height='650' webkitallowfullscreen mozallowfullscreen allowfullscreen frameborder='0'></iframe>

[La timeline en grand format](https://cdn.knightlab.com/libs/timeline3/latest/embed/index.html?source=1ZgnK7tp0L8hBm3_MwlHLURJoUwD0Ro7ydz3KyVyDHmM&font=Default&lang=en&initial_zoom=2&height=650)


__Exercices__ :

- Parcourir la timeline

- Répondre aux question sur Wooclap en cliquant [ici](https://app.wooclap.com/RQTZAO?from=event-page) ou en flashant le QR code ci-dessous

![](./images/qr_code_wooclap_debut_numerique.png)



<!-- La timeline montre que le numérique est une histoire scientifique et technique, mais aussi une histoire politique à travers les institutions mises en place pour développer Internet et réguler le réseau, une histoire culturelle à travers les pratiques des outils numériques, leurs inscriptions dans des oeuvres littéraires (Azimov), cinématographiques, une histoire des transformations sociales (le télétravail, les sites de rencontre, les réseaux sociaux) -->



## Internet : une innovation sociotechnique


```{note}
Les informations techniques contenues dans cette partie sont issues du très bon sites <a href="https://www.infoforall.fr/act/snt/cat/internet/"></a>
```


Internet est le nom donné au protocole permettant à des ordinateurs de communiquer à distance, c'est-à-dire de s'échanger des informations. Ce protocole est le __TCP/IP__, qui signifie "Transmission Control Protocol/__Internet__ Protocol". Il a été mis au point en __1973__ par Vinton Cerf et Robert Kahn dans le cadre du projet __ARPANET__ initié en __1966__ sous l'égide de l'Information Processing Techniques Office (IPTO). L'IPTO est lui-même une subdivision de l'Advanced Research Projetcs Agency. L'ARPA est une agence mise en place en 1958 par le Département américain de la Défense en réponse à l'envoi du premier satellite Spoutnik par l'Union soviétique.

La première démonstration d'une communication en réseau entre deux ordinateurs a eu lieu le 9 décembre 1968 avec en vedette Doug Engelbart. Alors qu'Engelbert et son équipe étaient dans le San Francisco’s Civic Auditorium, ils ont réussi à interagir avec un autre ordinateur situé dans leur laboratoire de l'université de Stanford. C'est aussi la première fois qu'on a utilisé une souris. Efin, cette démonstration est considérée comme "the mother of all demos".

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

Toutefois, il faut bien comprendre que les concepts qui sont au fondement d'Internet émergent dans des communautés marquées par la culture hippie et les normes de l’ethos scientifiques telles que décrites par Merton {cite:p}`mertonSociologyScienceTheoretical1973` : communalisme, universalisme. Par exemple, Steward Brand, figure de la mouvance hippie à San Francisco et proche d'Engelbart, va être à l'origine du _World Earth Catalog_, sorte de Wikipedia papier avant l'heure dans lequel n'importe qui peut publier ses trucs et astuces (une recette de cuisine, un mode d'emploi pour construire son ordinateur, etc.). On retrouve ainsi l'idée d'un savoir distribué.

![](./images/whole_earth_catalog.jpeg)

Enfin, Internet et les protocoles qui sont derrières constituent des innovations sociotechniques dans la mesure où elles conduisent à la création de nouvelles institutions dont le rôle va être de réguler le trafic sur les réseaux, gérer les adresses IP, etc.




# The Woman Dancing Emoji &#128131;

Les émojis est le thème imposé de cette année. Pour initier l'exercice d'implosion, on s'intéressera en particulier à l'émoji qui représente une femme en robe rouge en train de danser.

![](https://em-content.zobj.net/social/emoji/woman-dancing.png)
