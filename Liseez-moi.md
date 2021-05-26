# Kitchen Android TV 9 Pie X96mini Amlogic S905W

Voici la cuisine pour créer votre .img Android TV 9 pie pour la X96mini Amlogic S905W

Tout est déjà décompressé dans les dossiers 

bin = contient tous les outils nécessaires pour cuisiner

level1 =  Contient les partitions séparé (Ne pas toucher)

level2 = contient les patitions décompressée
system.PARTITION + vendor.PARTITION + product.PARTITION + odm.PARTITION 

Il vous suffit de modifier les fichiers que vous souhaitez (c'est ici que vous pouvez rajouter, supprimer, modifier les fichiers systèmes d'Android TV)

level3 = Contiens les partitions 
boot.PARTITION + recovery.PARTITION logo.PARTITION + aml_dtb.PARTITION 

Une fois que vous avez modifié tous ce que vous souhaitez vous pouvez créer le fichier .img en respectant cet ordre.

1. _pack_level3.bat
2. _pack_level2.bat
3. _pack_level1

Une fois terminé, vous retrouvez votre .img dans le dossier "out"

Il vous suffit juste de clignoter votre X96mini avec USB_Burning_Tool et votre .img

MinerHack
Basé sur vtx_kitchen_v4

Android TV 9 Pie pour X96mini S905W (Inclus = YoutubeTV + VLC) APK mis à jours
