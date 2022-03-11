Noms:
Sebastien Leduc - 300066083
Tristan Pender - 300065847

Quand vous rouler le programme en utilisant main.py, le fichier "img2" sera créé avec les résulats. Nous avons calculé le MOTA des images 85 à 467.

Pour le tracking des voitures rouler les fonction (ligne 327 à 330): 
populate_variables(files, "3")
create_folder("img2")
first_image_init("3")
fn, fp, ids, gt_t = use_iou()

Pour le tracking des piétons rouler les fonction (ligne 327 à 330): 
populate_variables(files, "1")
create_folder("img2")
first_image_init("1")
fn, fp, ids, gt_t = use_iou()

MOTA reçu pour les voitures: 0.95039...
MOTA reçu pour les piétons: 0.68754...


In the future, we wish to remove global variables to allow for clearer code. 