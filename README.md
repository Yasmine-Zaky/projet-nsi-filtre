# projet-nsi-filtre

## Description du projet

  Dans ce projet, je vais créer une application qui permet de modifier la luminosité, le contraste et floutage. Vous pourriez aussi jouer avec le format de l'image et pouvoir ajouter des nouveaux filtres (couleurs, rajout d'accessoires) pour embélir la photo souhaitée.


## Quelques problèmes pouvant apparaître sur la route  

  - Inserrer l'image souhaiter avec le bon format (fomat réel) 
  - Créer un filtre pouvant détecter le visage (comme instagram)
  - Pixel (image pas net)


## MVP
  
  - Premièrement, je vais changer quelques couleurs, formes, rotation et lumière dans l'image souhaitée
  - Deuxièment, je vais créer des filtres pour embélir l'image (visage, couleurs)
  - Troisièmement, je vais faire toujours attention aux pixels et au format de l'image (ne pas déformer et garder la netteté de l'image) 
  
 
## Liste des fonctions 
 
 ```
  def filtre (image, couleurs, décormation du visage, accessoires):
      """
      La fonction mettra le filtre choisi par la personne, noir et blanc - nuance de                 couleurs
      """
  
  def blur (image,):
       """
       La fonction mettra l'image en flou avec différentes capacités de floutage, de 0 - 100
        """
 
 def format (image,):
      """
      La fonction s'adaptera avec la forme d'image choisi par la personne, JPEG - PNG - JPG - JFIF - PJP - PJPEG - SVG - WEBP
      """
      
 def éclairage (image, luminausité , contraste):
      """
      La fonction pourra augmenter/baisser la luminausité et le contraste, de 0 - 100
      """
      
def accessoires (image, chapeau, maquillage, boucles d'oreille, oreille de lapin): 
      """
      La fonction mettra tout ce que la personne séléctionera dans le choix d'accessoire
      """   
```


## Jeux de tests

Nous allons tester si les filtres et les accessoires seront compatible avec l'image choisie (les bonnes couleurs et le bon repérage de visage).
