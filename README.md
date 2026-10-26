# Medusa Record
*Une voix. Cent têtes.*

![Medusa Record](https://raw.githubusercontent.com/Alpharid/ACH/main/web/assets/filiales/medusa-1.webp)

Medusa Record est un logiciel pour Windows qui guide l'enregistrement d'un **clip a cappella en mosaïque**. Tu
chantes une voix par prise (percussions, basse, chœurs, aigu, mélodie…) et il assemble toutes tes têtes dans une
grille de 1 à 99 vignettes, synchronisées, mixées et exportées en MP4. Pas besoin de logiciel de montage.

Ce dépôt ne contient **aucun code** : seulement les installeurs, dans l'onglet [**Releases**](../../releases).

## Ce qu'il fait
- **Mes clips** : un clip = un dossier ; tu choisis le nombre de vignettes (1 à 99), la durée, le format
  (16:9 YouTube, 1:1, 9:16 Reels / TikTok), le mode Guidé ou Libre, le tempo et le clic.
- **Un guide pour chaque prise** : quoi chanter et comment, décompte, clic, et les prises déjà faites dans le casque.
- **Accordeur** et vumètre dans le studio, caméra en direct dans la vignette en cours.
- **Synchro automatique** : mesure de la latence au premier lancement, recalage sur un claquement de mains au début
  de la prise.
- **Mode Avancé** : volume, panoramique, décalage de chaque voix, anciennes prises, retard de la caméra, réglages
  d'export.
- **Export MP4** au volume normalisé, et **mises à jour automatiques** de la version installée.

## Installer (Windows 10/11, 64 bits)
1. Ouvrir les [Releases](../../releases) et télécharger, dans la plus récente, `MedusaRecord-<version>-setup.exe`.
   Pour l'instant, toutes les versions sont des versions de test (*Pre-release*).
2. Le lancer. Windows peut afficher « Windows a protégé votre ordinateur » (le logiciel n'est pas signé) :
   cliquer sur **Informations complémentaires** puis **Exécuter quand même**.
3. Le logiciel s'installe dans votre profil (aucun droit administrateur), avec un raccourci sur le Bureau et dans le
   menu Démarrer. Pour le retirer : Paramètres › Applications › Medusa Record › Désinstaller (vos clips et réglages
   sont gardés).

Sans installation : le `.zip` de la même Release, à décompresser, puis lancer `Medusa Record.exe` (cette copie-là ne
se met pas à jour toute seule).

## Il faut
- Windows 10 ou 11, 64 bits ;
- une caméra et un micro ;
- **un casque**, pour entendre les prises déjà faites sans qu'elles repassent dans le micro.

## Versions
- **Pre-release** = version de test (UNSTABLE) ; **Latest** = version stable (aucune pour l'instant).
- Dans le logiciel, *Avancé › Logiciel* permet de choisir de recevoir aussi les versions de test, ou seulement les
  stables.

## État
Alpha : le cœur marche (prises synchronisées, guide, accordeur, export). En préparation : finir une prise avant la fin
du clip et la faire boucler.

ffmpeg est fourni avec le logiciel (build de gyan.dev, licence GPL, texte dans `resources\bin\ffmpeg-LICENSE.txt`).

Filiale d'[Alpharium](https://alpharid.github.io/ACH/#filiale/medusa) — division β Apps.
