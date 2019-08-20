# inventaire_rues
inventaire des rues d'une commune

le but est de générer pour une commune de France un fichier (au format csv) listant l'ensemble des rues qui la compose en récupérant
  - le code FANTOIR
  - l'identifiant OSM (quand il s'agit d'une relation)
  
Ce fichier est destiné à préparer un import de ces rues dans WikiData
Ce travail est en lien avec la ésentation faite au SOTM France 2019 sur l'inventaire des rues de Lyon

# Utilisation

./inventaire_voies.py 69019

(qui va générer un fichier 69019_BELLEVILLE.csv)
