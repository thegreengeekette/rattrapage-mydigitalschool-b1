# Gestionnaire de livres pour une bibliothèque (stockage en fichier JSON)

Le terme "application web" est ici employé pour parler de notre site web. :)

## Fonctionnalités attendues :

- L'application web doit possèder un header avec un menu permettant d'accèder à ses différentes pages : "Les livres" et "Les livres de la sélection". Elle a également un footer qui affiche un copyright.

### Sur la page "Les livres" :

- L'application web doit charger la liste des livres existants avec leurs détails depuis un fichier JSON.
- L'application web doit permettre à l'utilisateur·ice d'ajouter un nouveau livre avec des détails tels que le titre, l'auteur, l'année de publication, le genre et une variable booléenne qui dit si le livre fait partie de la sélection, grâce à un formulaire en dessous. Les livres ajoutés sont automatiquement sauvegardés dans le fichier JSON.
- L'application web doit permettre à l'utilisateur·ice de modifier les détails d'un livre existant, y compris le titre, l'auteur, l'année de publication, le genre et la variable booléenne qui dit si le livre fait partie de la sélection, et d'enregistrer les changements.

### Sur la page "Les livres de la sélection" :

- Cette page affiche (sans modification) la liste des livres qui font parti de la sélection.
- ATTENTION, la liste des livres ne doit pas être chargée à nouveau, elle doit avoir été stockée dans une variable de session globale.

## Points d'attention :

- Offrez une interface utilisateur conviviale permettant de modifier le contenu des livres existants facilement. Le CSS est encouragé pour que votre design soit attractif, mais non obligatoire. L'important c'est le code PHP, même si vos compétences en UI/US seront appréciées en bonus.
- Assurez-vous que les livres restent persistants même après la fermeture et le redémarrage de l'application en lisant et en écrivant le contenu du fichier JSON au chargement et à la modification de la page, respectivement.
- Veillez à la validation des données entrées par les utilisateur·ice·s pour garantir la sécurité et l'intégrité des données stockées dans le fichier JSON.
- N'oubliez pas de prendre en charge la gestion des erreurs pour informer les utilisateurs des problèmes rencontrés lors de l'interaction avec l'application.
- Votre code sera commenté pour les fonctionnalités importantes.
