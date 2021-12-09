Bonjour,

Mon projet consiste à effectuer un site pour un commercial. J'ai décidé de me pencher sur les simulateurs de voiture de la grande marque Fanatec.
Tout d'abord, j'ai commencé par une navbar en position fixe qui contient les informations "accueil", "projet", "contacts", et "a propos". 
Ainsi, lorsqu'on clique sur ces liens, cela nous dirige directement sur l'endroit de la page associé.
Bien sur, il faut appellé les ID dans le code pour que cela fonctionne. (ex : id = "Projets").

Ensuite, en titre du site j'ai mis mon nom prénom ainsi que de ma date de naissance dans un div titre.
Suivi d'une photo de profil qui est arrondie grace a des réglages de width, de height, et de border radius.

Après nous trouvons un carroussel contenant des images. Il y a une image qui porte le nom de la marque et les deux dernières qui portent sur de excellent simulateurs. 
Assetto corsa competizione et Iracing.

Puis vient les projet. En réalité, il s'agit des éléments que l'on peut acheter sur le site même. 
Cela se présente sous forme de flip-card ou lorsque celle-ci se retourne nous apercevons une breve description ainsi que d'un lien qui nous amène directement sur le site fanatec avec la bonne référence.

Puis vient le a propos qui est une petite description de moi même qui est contenue dans une class"bg-dark text-light".
Ce qui permet d'avoir un background (bg) foncé et du text blanc (text-light).
Dans cette div, j'ai mis une autre div class "container py-5".
Le container permet que la div aura des marges automatiques et le py-5 correspond à un padding top et bottom car le y signifie both.
Ainsi, le text sera centré et aura un padding.

Ensuite, le formulaire de contact.
Il se situe dans une div qui a comme caractère, container, comme ceci il y aura des marges automatiques.
Ensuite, les zones de texte sont placées dans des div de class mb-3 ce qui signifie margin-bottom : 3.
De ce fait, il y aura un espacement entre chaque zone de texte afin qu'elles ne soient pas trop proches.

Et enfin, le footer.
Celui-ci est stocker dans un div de class "bas" (pour dire que c'est tout en bas de l'écran) Je l'ai mis dans un div comme ceci afin de lui appliquer un padding-top:30px.
Ensuite, le footer est stocker dans une div de class bg-dark text-center text-white.
Cela permet d'avoir un background foncé (bg-dark) d'avoir le text centré (text-center) et d'avoir le text en blanc (text-white).
Ce footer contient 2 liens, mon lien github et de mon lien discord si jamais les personnes veulent communiquer avec moi ou encore voir mes projets.
j'ai terminé ce footer en mettant une dernière fois mon nom et prénom avec un p-3 (padding)en guise de signature.



Pour terminer, mon code contient des termes spéciaux comme par exemple p-3. Cela correspond à la bibliothèque bootstrape. A savoir que j'ai modifier certaine chose dans les codes que nous propose bootstrap.



