# seuil. — Simulateur immobilier

Application statique indépendante, sans dépendance, sans serveur de calcul et sans montant prérempli.

## Utilisation

Ouvrir `index.html` dans un navigateur ou consulter la version GitHub Pages :
https://leefranck.github.io/quittance-loyerV3/simulateur-pret/

Renseigner le prix, les frais de notaire, l'apport de départ, la durée, le taux nominal, l'assurance et au moins un revenu retenu positif. Les champs facultatifs vides comptent pour zéro. Si des loyers sont saisis, leur part retenue doit être explicitement renseignée. La réinitialisation vide les champs.

## Fonctionnalités

Mensualité et endettement en direct, deux modes d'assurance, comparaison d'hypothèses, trois scénarios, import/export JSON, échéancier CSV et impression.

Les calculs restent dans le navigateur. La mémorisation locale est facultative et désactivée à la première visite. Aucun chiffre personnel n'est inclus dans les fichiers publiés.

## Limites

Prêt amortissable à taux fixe et assurance constante. Les règles et sources sont documentées dans l'interface. Une simulation n'est pas un accord bancaire. Les dépenses d'exploitation, la fiscalité et un éventuel loyer personnel conservé ne sont pas simulés.

## Structure

- `index.html` : interface et documentation.
- `style.css` : présentation adaptative ordinateur/mobile.
- `app.js` : calculs, validations, scénarios et exports.

Ce dossier est autonome et ne modifie pas l'outil de quittances situé à la racine du dépôt.
