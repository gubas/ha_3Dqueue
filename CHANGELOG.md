# Changelog

## [0.2.0] - 2025-11-22

### Changed
- Migration de Flask vers Bottle (framework ultra-léger)
- Simplification drastique : uniquement liens MakerWorld
- Optimisation Dockerfile (Alpine Linux optimisé)
- Réduction des dépendances (2 au lieu de 3)

### Added
- Détection automatique du nom d'utilisateur Home Assistant via header X-Ingress-User
- Champs optionnels : nom du modèle et requester auto-détectés
- Documentation complète mise à jour

### Removed
- Support Thingiverse
- Upload de fichiers STL
- Estimation de poids via PrusaSlicer
- Vérification de stock de filament
- PrusaSlicer CLI du conteneur Docker
- BeautifulSoup, numpy-stl, Werkzeug

### Fixed
- Image Docker plus légère (~90 MB vs ~300 MB)
- Démarrage plus rapide
- Interface simplifiée et plus claire
