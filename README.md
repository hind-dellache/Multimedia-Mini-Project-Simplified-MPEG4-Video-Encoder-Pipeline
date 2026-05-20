Pipeline d'Encodage Vidéo MPEG-4
Mini-projet réalisé dans le cadre du module Systèmes Multimédia (Master 1 IL, USTHB 2025/2026).
Ce projet implémente en Python un encodeur/décodeur vidéo simplifié inspiré du standard MPEG-4. Il prend en entrée un dossier d'images séquentielles et produit un fichier binaire compressé .bin, que l'on peut ensuite décoder pour reconstruire les images d'origine.
Le pipeline couvre la conversion d'espace colorimétrique (YCbCr), la compression par DCT sur les I-frames, l'estimation de mouvement sur les P-frames, et le codage entropique par RLE + LZW.
Lancer le projet
bashpip install numpy opencv-python matplotlib
python main_encode.py
python main_decode.py
DELLACHE Hind & BENCHABANE Sarah — Encadrante : B. Abadli