<h1 align="center">Inception-of-Things (IoT)</h1>

Projet post tronc-commun de [42](https://42.fr/), dont le but est de configurer et gérer des clusters Kubernetes légers avec K3s et K3d, ainsi que de déployer des applications web et des pipelines CI/CD.

Ce projet couvre les aspects suivants :

- Configuration de clusters Kubernetes avec K3s et K3d.
- Déploiement de multiples applications web.
- Mise en place de pipelines CI/CD avec Argo CD.

---

### Pré-requis :

- GNU Make >= 3.81
- VirtualBox >= 7.
- Vagrant >= 2.4.
- Make >= 3.81.

### Décomposition des differentes parties :

#### Partie 1 : K3s et Vagrant
> Configuration de machines virtuelles avec Vagrant, la mise en place d'un cluster Kubernetes léger avec K3s, et l'utilisation de `kubectl` pour gérer le cluster.

##### Partie 2 : K3s et trois applications simples
> Déploiement de plusieurs applications web sur un cluster K3s. Inclut la configuration des applications pour être accessibles via des noms d'hôte spécifiques et la mise en place de répliques pour l'une des applications.

##### Partie 3 : K3d et Argo CD
> Création d'un cluster Kubernetes avec K3d et de la mise en place de pipelines CI/CD avec Argo CD. Comprend la configuration de namespaces pour Argo CD et le déploiement automatique d'applications à partir d'un dépôt GitHub.

##### Bonus : Gitlab
> Intégration de Gitlab dans le cluster Kubernetes. Il inclut l'installation et la configuration d'une instance Gitlab locale, la création d'un namespace dédié, et l'intégration de Gitlab avec les pipelines CI/CD configurés dans la Partie 3.

### Commandes disponibles :

- `make` : Lancement du projet.
- `make down` : Détruit les machines virtuelles.
- `make s` : Connexion en SSH au serveur.
- `make sw` : Connexion en SSH au worker.
- `make clean` : Nettoie le projet.
- `make fclean` : Détruit et nettoie le projet.

---

### Correction :

| |
| --- |
| Pas encore corrigé ! |

---
