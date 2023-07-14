# [Lis le README avant de commencer à lire ce document](README.md)
## Voici les étapes simples pour contourner les restrictions MDM sur ton iPad.

### 1. Commence par télécharger les applications nécessaires sur ton ordinateur Windows 10 :
  - Télécharge l'application iBackupBot sur ton ordinateur Windows 10.
  - Télécharge l'application Apple iTunes sur ton PC Windows 10 (cela permettra à ton ordinateur d'accéder aux fichiers de ton iPad).
  - Connecte ton iPad à l'ordinateur à l'aide d'un câble USB Lightning.
  - Lorsque ton iPad te demande si tu fais confiance à l'ordinateur, clique sur "Oui".
  - Dans les paramètres de ton iPad, vas dans "Affichage et luminosité" et configure l'extinction de l'écran sur "Jamais".
  - Si nécessaire, enlève le mot de passe de ton iPad.
  
### 2. Ensuite, sauvegarde tous tes fichiers de l'iPad :
  - Fais une sauvegarde depuis iBackupBot de tes fichiers.
  - Copie-colle la une fois.
    - L'une des sauvegardes sera modifiée.
    - L'autre sauvegarde sera une sauvegarde normale au cas où.
  - Renomme tes sauvegardes 'modifiée' et 'normale'.

### 3. Maintenant, passons à la partie principale où nous allons modifier les profils de configuration sur ton appareil :
  - Ouvre la sauvegarde modifiée dans l'application iBackupBot sur ton ordinateur.
  - Dans le répertoire principal, recherche le terme "config".
  - Clique sur le dossier "ConfigurationProfiles".
  - Supprime les profils qui contiennent des commandes de restriction :
    - Attention : SUPPRIME UNIQUEMENT les fichiers qui empêchent ton appareil de télécharger ou de se connecter à des applications ou des VPN, et rien d'autre.
    - Un profil qui restreint les VPN contiendra une liste de réseaux VPN et de leurs adresses (par exemple : "hotspotshield.com"). Supprime ce fichier.
    - Un profil qui empêche le téléchargement d'applications depuis l'App Store contiendra du code qui bloque les téléchargements (ces fichiers sont facilement reconnaissables).
    - Exemple :
      - Profil VPN : 8eab4842..
      - Restrictions 1 : 973342024b65ca..
      - Restrictions 2 : b8cec5a9..

### 4. Maintenant, charge la sauvegarde modifiée (sans restrictions) sur ton iPad scolaire :
  - Sélectionne tout le répertoire de la sauvegarde modifiée.
  - Clique sur le bouton de chargement de la sauvegarde en haut de l'écran.
  - Attends que la sauvegarde se charge sur ton iPad.
  - Ton iPad redémarrera et se chargera, cela prendra un certain temps.

### 5. Vérifie que tout fonctionne correctement :
  - Lance des applications et assure-toi qu'elles fonctionnent.
