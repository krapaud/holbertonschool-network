# Networking Basics #1

Ce dossier contient des exercices avancés sur la configuration et l'administration réseau.

## Objectifs d'apprentissage

- Configurer localhost et les fichiers hosts
- Afficher les adresses IP actives sur la machine
- Gérer les ports en écoute
- Manipuler les configurations réseau

## Fichiers

### 0-change_your_home_IP

Script Bash qui configure Ubuntu pour :

- Résoudre `localhost` vers `127.0.0.2`
- Résoudre `facebook.com` vers `8.8.8.8`

Modifie le fichier `/etc/hosts` pour changer la résolution DNS locale.

**Utilisation :**

```bash
sudo ./0-change_your_home_IP
```

⚠️ Nécessite les privilèges root/sudo

### 1-show_attached_IPs

Script Bash qui affiche toutes les adresses IPv4 actives sur la machine.

**Utilisation :**

```bash
./1-show_attached_IPs
```

### 2-port_listening_on_localhost

Script Bash qui écoute sur le port 98 en localhost.

**Utilisation :**

```bash
./2-port_listening_on_localhost
```

## Prérequis

- Système d'exploitation basé sur Linux (Ubuntu recommandé)
- Accès sudo pour certains scripts
- Commandes réseau de base : `ifconfig`, `netstat`, `nc`

## Utilisation

Rendre les scripts exécutables :

```bash
chmod +x <nom_du_script>
```

## Notes importantes

⚠️ La modification du fichier `/etc/hosts` peut affecter la résolution DNS de votre système. Assurez-vous de comprendre les implications avant d'exécuter ces scripts.

## Auteur

Projet réalisé dans le cadre de la formation Holberton School.
