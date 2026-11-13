# FasoCompta Bureau

**La gestion de votre entreprise, 100 % hors-ligne, sur votre ordinateur Windows.**

FasoCompta Bureau est la version bureau de FasoCompta : caisse (POS), stock, clients et dettes, factures et devis en PDF, finances et rapports — **sans aucune connexion internet**. Vos données restent chez vous, sur votre machine.

## Téléchargement

- **Installeur Windows (v1.0.3)** : [FasoCompta-Bureau-Setup-1.0.3.exe](https://github.com/mahamadoubmaiga2025-hub/fasocompta-bureau/releases/download/v1.0.3/FasoCompta-Bureau-Setup-1.0.3.exe) (118 411 366 octets — SHA-256 : `307f9bb5f38ceff22afe0fae056c49faffb3e743715356eaa3768aeb4ae508af`)
- **Guide d'utilisation (PDF)** : [Guide-FasoCompta-Bureau.pdf](https://github.com/mahamadoubmaiga2025-hub/fasocompta-bureau/releases/download/v1.0.3/Guide-FasoCompta-Bureau.pdf)

## Nouveautés de la v1.0.3

- **Licences infalsifiables** : les clés d'activation sont maintenant signées (Ed25519) — l'application ne contient qu'une clé publique de vérification, impossible de fabriquer une clé sans la clé privée du vendeur. Les activations déjà enregistrées restent honorées ; les nouvelles clés sont plus longues et se collent (copier-coller).

Et tout le contenu de la v1.0.2 (audit de professionnalisation du 13/11/2026) :

- **Sauvegardes fiables et vérifiées** : chaque sauvegarde est une image complète et cohérente de la base, contrôlée avant d'être annoncée — restauration testée de bout en bout
- **Multi-postes durci** : rôles vérifiés côté serveur, inscription des postes par code d'appairage (rôle caissier par défaut), sessions de 12 h, reconnexion automatique, rafraîchissement des données entre postes en temps réel
- **Base de données renforcée** : migrations versionnées avec sauvegarde préalable, index de performance, écritures simultanées sans perte (testé : 600/600)
- **Écran Diagnostic** intégré (versions, état de la base et du serveur, dernière sauvegarde) avec export pour le support
- Secteurs : **devis ouverts pour le Transport, caisse ouverte pour les Services**
- Connexion 100 % locale (identifiant + mot de passe/PIN, sans Google), bouton « Découvrir la démo », polices intégrées, aucun appel réseau — 100 % hors-ligne réel, vérifié

## Installation

1. Téléchargez l'installeur ci-dessus.
2. Double-cliquez dessus et acceptez le contrat de licence.
3. Au premier lancement : choisissez le mode de poste, créez votre compte patron, puis votre entreprise et son secteur d'activité.

Le guide PDF explique tout, pas à pas.

## 9 secteurs d'activité

Boutique, restaurant, pharmacie, station-service, transport, services, distribution (commerce de gros), production (recettes et coût de revient), global. Chaque secteur ne voit que ses modules, avec un pack de démarrage adapté.

## Multi-postes en réseau local

Plusieurs postes dans la même boutique, **sans internet** : un poste principal, les autres s'y relient par un code d'appairage (détection automatique, aide pare-feu intégrée).

## Autres fonctions

- Activation par clé de licence (1 mois, 3 mois, 6 mois, 1 an, à vie)
- Sauvegarde chiffrée (.fcbak) automatique chaque jour et restauration protégée
- Verrouillage automatique après 15 minutes d'inactivité
- Mode démo intégré pour découvrir le logiciel

---

© Mahamadou Boubacar Maïga — Tous droits réservés. Le code source de FasoCompta Bureau n'est pas publié dans ce dépôt ; seuls l'installeur et le guide y sont distribués.
