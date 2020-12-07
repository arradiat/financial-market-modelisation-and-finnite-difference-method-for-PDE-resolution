# financial-market-modelisation-and-finnite-difference-method-for-PDE-resolution
 Ce projet réalisé en binome consiste en la modélisation d’un marché financier afin de déterminer le prix d’options européennes. Le marché financier est composé de deux actifs que l’on peut échanger à un prix fixé par le marché : — un actif que l’on appelle sans risque dont le prix à l’instant t est noté St0 que l’on suppose connu dès l’instant initial 0 (ce prix est une variable aléatoire déterministe), — un actif risqué dont le prix St à l’instant t est une variable aléatoire (typiquement une action), dont on modélisera la loi par la suite. Nous voulons donc déterminer le prix P qu’un vendeur doit faire payé à un investisseur à l’instant initiale pour qu’à la date T l’investisseur reçoive f(ST) mais également la couverture que doit mettre en place le vendeur pour couvrir ces risques. En resumé on cherche la proportion d’argent investie dans l’actif risqué et la proportion d’argent investie dans l’actif sans risque à n’importe quelle date pour qu’à la date T lorsqu’on vend tout pour récuperer du cash le vendeur a exactement la somme f(ST). Pour résoudre ce problème nous modéliserons dans un premier temps l’évolution des prix de manière discrète avec une progression par arbre en suivant le modèle de Cox-Ross-Rubinstein, puis dans un second temps nous modéliserons l’évolution des prix de manière continue avec le modèle de Black-Scholes. Dans un troisième temps nous étudierons la convergence du prix donné par le modèle de Cox-Ross-Rubinstein vers celui donné par le modèle de Black-Scholes.
