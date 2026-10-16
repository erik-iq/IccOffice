# Cuvée — maquette interactive

Ouvrir `index.html` dans un navigateur récent. Aucun serveur, téléchargement de dépendances ou accès Internet n’est nécessaire. Le fichier contient ses styles, scripts et illustrations.

## Parcours proposés

- Tableau de bord : indicateurs, graphique avec sélection de période et points d’attention.
- Clients : recherche, ajout et consultation de l’historique.
- Commandes : création, préparation et confirmation de livraison. La livraison débite le stock en bouteilles.
- Cave : lots en vrac, journal et ajout de mouvements. Une mise de 75 cl diminue le vrac et ajoute les bouteilles au millésime concerné.
- Factures : création depuis une commande livrée, échéances, règlement fictif et impression d’un aperçu.
- Vins et stocks : catalogue, disponibilités et filtre de stock bas.
- Export CSV des données de chaque rubrique.

Les données et le domaine sont fictifs. Les montants sont indicatifs, sans calcul de TVA. La date de référence est le 16 octobre 2026. Aucun paiement, envoi de message ou document officiel n’est effectué. La maquette ne réalise pas de contrôle de cave réglementaire et ne représente pas une application de production.

Les essais sont conservés dans le stockage local du navigateur lorsqu’il est disponible. Le bouton « Réinitialiser » restaure les données d’exemple. Le fonctionnement ne dépend d’aucune requête vers un service externe. Le nom Cuvée est un nom de travail, sans lien avec l’éditeur ICC Office.

Validation : parcours de navigation, recherche, client, commande, livraison et stock, facture et règlement, volumes de cave, export, persistance et réinitialisation testés avec Chromium ; affichage et navigation mobile vérifiés à 390 px.

## Présentation client

Dans le menu latéral, « Présentation client » ouvre un diaporama de dix diapositives dans un nouvel onglet. Il présente les parcours de la maquette, les bénéfices à évaluer et les étapes proposées pour le projet.

- Navigation : boutons, flèches du clavier, début/fin et plan des diapositives.
- Plein écran : bouton ou touche **F** ; un bouton permet d’en sortir.
- Plan : bouton ou touche **O** ; **Échap** pour le fermer.
- PowerPoint : téléchargement du fichier `.pptx` depuis la barre supérieure, avec notes pour le présentateur.
- Sur téléphone : lecture adaptée, boutons et balayage horizontal.

Conserver le dossier `presentation/` avec `index.html`, le PowerPoint et ses images `assets/`. Pour un usage hors ligne, extraire le dossier complet avant d’ouvrir la maquette. Aucun hébergement ou service externe n’est nécessaire.

Le générateur `presentation/build_presentation.py` permet de reconstruire le HTML et le PowerPoint à partir des contenus et des captures incluses (Python, `python-pptx` et `Pillow` nécessaires uniquement à la reconstruction).

Validation de cet ajout : ouverture dans un nouvel onglet sur ordinateur et mobile, dix diapositives, navigation clavier/boutons, plan, plein écran, liens de diapositives et téléchargement PowerPoint testés avec Chromium. Le PowerPoint a également été converti pour contrôler visuellement ses dix diapositives.
