**Axepta Online – Magento 2 Payment Module**


![License](https://img.shields.io/badge/License-MIT-green)
![PHP](https://img.shields.io/badge/PHP-%3E=8.2-blue)
![Magento](https://img.shields.io/badge/Magento-2.4.8-orange)
[![Release](https://img.shields.io/badge/Release-2.0.0-blue)](../../releases/latest)
![Downloads](https://img.shields.io/badge/Downloads-0-lightgrey)



Overview

The Axepta Online module for Magento 2 enables merchants to process secure online payments through Axepta BNP Paribas.
It integrates seamlessly with Magento 2 and supports a wide range of payment methods.

💳 Supported Payment Methods

CB

Visa

Mastercard

American Express

Apple Pay (on checkout page)

Google Pay (on checkout page)

PayPal

⚙️ Features

Automatic capture

Manual capture

Delayed capture

📦 Installation
Manual Installation

Download the ZIP archive

Extract and copy the folder into /app/code/Axepta/Online/

Enable the module and upgrade Magento:

bin/magento module:enable Axepta_Online
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento cache:flush

🔐 Digital Signature

Signature File: axepta-magento-2.0.0.zip.sig

The release is signed using an RSA private key.
You can verify the authenticity and integrity of the downloaded ZIP using the signature file and the public certificate.

✅ Verification Instructions
Step 1: Download Required Files
Download the public certificate (from our public repository)
`curl -LO https://raw.githubusercontent.com/AxeptaBNPParibas/.github/refs/heads/main/axepta-online-github.crt`

Step 2: Verify the Signature
Extract the public key
`openssl x509 -in axepta-online-github.crt -pubkey -noout > public_key.pem`

Verify the signature against the downloaded ZIP
`openssl dgst -sha256 -verify public_key.pem -signature axepta-magento-2.0.0.zip.sig axepta-magento-2.0.0.zip`


Expected result if verification succeeds:

Verified OK


⚠️ Security Warning: Only use this release if signature verification succeeds.
A failed verification means the file may have been tampered with.

⬇️ Download

Download the latest release here:

[📥 Download Latest Release](../../releases/latest)

Each release includes:

ZIP package

RSA digital signature

📞 Support

📧 assistance.ecommerce@bnpparibas.com

--------------------------------------------------------------------------

Axepta Online – Module de paiement Magento 2

![License](https://img.shields.io/badge/License-MIT-green)
![PHP](https://img.shields.io/badge/PHP-%3E=8.2-blue)
![Magento](https://img.shields.io/badge/Magento-2.4.8-orange)
[![Release](https://img.shields.io/badge/Release-2.0.0-blue)](../../releases/latest)
![Downloads](https://img.shields.io/badge/Downloads-0-lightgrey)



Présentation

Le module Axepta Online pour Magento 2 permet aux marchands d’accepter des paiements sécurisés en ligne via Axepta BNP Paribas.
Il s’intègre parfaitement à Magento 2 et prend en charge un large éventail de moyens de paiement.

💳 Moyens de paiement

CB

Visa

Mastercard

American Express

Apple Pay (sur la page de paiement)

Google Pay (sur la page de paiement)

PayPal

⚙️ Fonctionnalités

Capture automatique

Capture manuelle

Capture différée

📦 Installation
Installation manuelle

Télécharger l’archive ZIP

Dézipper et copier le dossier dans /app/code/Axepta/Online/

Activer le module et mettre Magento à jour :

bin/magento module:enable Axepta_Online
bin/magento setup:upgrade
bin/magento setup:di:compile
bin/magento cache:flush

🔐 Signature numérique

Fichier de signature : axepta-magento-2.0.0.zip.sig

La release est signée avec une clé privée RSA.
Vous pouvez vérifier l’authenticité et l’intégrité du fichier ZIP téléchargé à l’aide du fichier de signature et du certificat public.

✅ Instructions de vérification
Étape 1 : Télécharger les fichiers requis
Télécharger le certificat public (depuis notre dépôt public)
`curl -LO https://raw.githubusercontent.com/AxeptaBNPParibas/.github/refs/heads/main/axepta-online-github.crt`

Étape 2 : Vérifier la signature
Extraire la clé publique
`openssl x509 -in axepta-online-github.crt -pubkey -noout > public_key.pem`

Vérifier la signature du ZIP téléchargé
`openssl dgst -sha256 -verify public_key.pem -signature axepta-magento-2.0.0.zip.sig axepta-magento-2.0.0.zip`


Résultat attendu si la vérification réussit :

Verified OK


⚠️ Avertissement de sécurité : N’utilisez cette version que si la vérification de la signature réussit.
Une vérification échouée signifie que le fichier a pu être altéré.

⬇️ Téléchargement

Téléchargez la dernière version ici :

[📥 Téléchargez la dernière version](../../releases/latest)

Chaque version contient :

Archive ZIP

Signature numérique RSA

📞 Support

📧 assistance.ecommerce@bnpparibas.com
