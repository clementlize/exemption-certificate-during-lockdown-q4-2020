# [Français] Générateur de certificat de déplacement

Version de la traduction: 1.0
Réalisé à partir du document officiel disponible sur le site [interieur.gouv.fr](https://www.interieur.gouv.fr/Actualites/L-actu-du-Ministere/Attestations-de-deplacement)

## Développer

### Installer le projet

```console
git clone https://github.com/LAB-MI/attestation-deplacement-derogatoire-q4-2020.git
cd attestation-deplacement-derogatoire-q4-2020
npm i
npm start
```

## Générer et tester le code de production

### Tester le code de production en local

#### Générer le code de production pour tester que le build fonctionne en entier

```console
npm run build:dev
```

#### Tester le code de production en local

```console
npx serve dist
```

Et visiter http://localhost:5000

Le code à déployer sera le contenu du dossier `dist`

## Crédits

Ce projet est une traduction du dépôt [attestation-deplacement-derogatoire-q4-2020](https://github.com/LAB-MI/attestation-deplacement-derogatoire-q4-2020), réalisé à partir d'un fork du dépôt [deplacement-covid-19](https://github.com/nesk/deplacement-covid-19) de lui-même réalisé à partir d'un fork du dépôt [covid-19-certificate](https://github.com/nesk/covid-19-certificate) de [Johann Pardanaud](https://github.com/nesk).

Les projets open source suivants ont été utilisés pour le développement de ce
service :

- [PDF-LIB](https://pdf-lib.js.org/)
- [qrcode](https://github.com/soldair/node-qrcode)
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/license)

# [English] Lockdown exemption certificate generator

Translation version: 1.0
Made using the english official document from [interieur.gouv.fr](https://www.interieur.gouv.fr/Actualites/L-actu-du-Ministere/Attestations-de-deplacement)

## Developing

### Installing project

```console
git clone https://github.com/clementlize/exemption-certificate-during-lockdown-q4-2020.git
cd exemption-certificate-during-lockdown-q4-2020
npm i
npm start
```

## Generating and testing production code

### Local testing of production code

#### Generating production code to test if the build is working properly

```console
npm run build:dev
```

#### Local testing of production code

```console
npx serve dist
```

And visit http://localhost:5000

The production code is located in the folder `dist`

## Credits

This project is a translation of the repository [attestation-deplacement-derogatoire-q4-2020](https://github.com/LAB-MI/attestation-deplacement-derogatoire-q4-2020), made from the repository [deplacement-covid-19](https://github.com/nesk/deplacement-covid-19), made itself from the repository [covid-19-certificate](https://github.com/nesk/covid-19-certificate) by [Johann Pardanaud](https://github.com/nesk).

To make this service, these open-source project have been used:

- [PDF-LIB](https://pdf-lib.js.org/)
- [qrcode](https://github.com/soldair/node-qrcode)
- [Bootstrap](https://getbootstrap.com/)
- [Font Awesome](https://fontawesome.com/license)


