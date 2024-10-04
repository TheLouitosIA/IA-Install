# IA-Install

Installation de Python
Si tu n’as pas encore installé Python, tu peux le télécharger sur python.org/downloads.
Assure-toi d’ajouter Python à ton PATH lors de l’installation (c’est une case à cocher pendant l'installation).


Installation de Jupyterlab
Jupyterlab te permettra de travailler sur un serveur distant et de ne pas t'inquiéter des capacités matérielles de ton propre ordinateur :
**pip install jupyterlab**

Installation de PyTorch
PyTorch est utilisé pour entraîner Llama. Pour l'installer, exécute la commande suivante dans ton terminal ou dans Jupyterlab : 
**pip install torch torchvision torchaudio**

Installation d’OpenCV et Tesseract OCR
Pour extraire le texte des plaques, tu auras besoin de deux outils : OpenCV pour traiter les images et Tesseract pour la reconnaissance optique de caractères :
**pip install opencv-python**

Pour installer Tesseract sur Windows, tu peux suivre les instructions ici :
Pour Windows : **https://github.com/UB-Mannheim/tesseract/wiki**
