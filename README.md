# La Relève — Sorbonne Nouvelle

Site statique de mobilisation étudiante. Ouvrir `index.html` dans un navigateur pour l’aperçu. L’image du campus se trouve dans `assets/sorbonne-nouvelle-campus.webp`.

## Contenus

Les actualités, événements et ressources sont dans l’objet `SITE_DATA`, en haut du script de `index.html`. Remplacez les informations de démonstration par des annonces vérifiées et datées. Les coordonnées et documents proposés par le collectif doivent être exacts et à jour.

## Formulaire

Le formulaire demande le prénom, l’adresse e-mail, le message et un accord obligatoire lié à la demande. Par défaut, il n’envoie rien. Pour recevoir et gérer les demandes, choisissez un prestataire de formulaire adapté, configurez un endpoint HTTPS avec accès administrateur, protection anti-spam, règles d’accès, suppression et durée de conservation, puis renseignez cette adresse dans `SITE_DATA.formEndpoint`. Ne mettez jamais de clé secrète dans le JavaScript public. Vérifiez également les conditions de traitement et la localisation/hébergement des données du prestataire avant collecte réelle. Testez l’envoi et la suppression avec des données fictives.

## Cookies et dépendances

Le bandeau s’affiche lorsqu’aucun choix valide n’est enregistré. Le choix (dont le refus) est mémorisé pendant six mois et peut être modifié via « Préférences cookies ». Cette maquette ne déclenche aucun outil d’audience. Si des traceurs ou contenus tiers sont ajoutés, bloquez leur chargement avant consentement et adaptez l’information, les catégories et le retrait du consentement. Tailwind CSS est chargé par CDN comme demandé ; pour une mise en production, une compilation locale permet de réduire la dépendance au CDN. La page n’ajoute pas de police distante.

## À compléter avant publication

- Le nom et l’adresse e-mail de Hichem Berhail sont indiqués comme point de contact du site et pour les demandes relatives aux données. Confirmer que cette personne est bien désignée pour ce rôle avant publication. Remplacer les autres champs `[À COMPLÉTER]` : identité/statut/adresse de l’éditeur, responsable de publication et qualité, hébergeur, identité du responsable de traitement, durées, destinataires, prestataire de formulaire et modalités d’exercice des droits.
- Vérifier l’adéquation des textes juridiques au collectif, au prestataire et au déploiement réels ; ces modèles ne constituent pas une validation juridique.
- Ajouter l’endpoint, vérifier la réception par les personnes administratrices, les contrôles anti-spam, les accès restreints et le parcours de suppression des demandes.
- Confirmer que le collectif dispose des droits nécessaires pour republier la photo et attribuer sa source/crédit si nécessaire.
- Remplacer les dates fictives et les ressources en attente. Vérifier les liens, le contenu mobile et le formulaire sur l’hébergement retenu.

## Sauvegarde

Conservez ensemble `index.html`, `README.md` et le dossier `assets/`. Pour toute modification, gardez une copie complète datée ou utilisez un dépôt privé avec accès limité. Ne placez pas de réponses au formulaire, mots de passe ou secrets dans ce dossier public.
