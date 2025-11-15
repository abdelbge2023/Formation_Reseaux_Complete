> ⚠️ ATTENTION : Ce fichier README ne doit pas être modifié. Toute modification pourrait affecter la documentation et le projet.

# Calculateur VLSM Professionnel

## Description
Ce projet est un **calculateur VLSM interactif et visuel**, conçu pour calculer et présenter des sous-réseaux IPv4 selon les besoins.  
Il permet de saisir une adresse réseau et son masque, le nombre de sous-réseaux et le nombre d'hôtes pour chaque sous-réseau, puis de générer automatiquement :  

- Les adresses réseau, première et dernière IP, et adresses broadcast.  
- Le préfixe minimal pour chaque sous-réseau.  
- Une **représentation graphique interactive** de chaque sous-réseau, avec longueur proportionnelle aux hôtes.  
- Des alertes visuelles si la demande dépasse la capacité du réseau principal.  
- La possibilité d’**exporter les résultats en PDF ou Excel**.

Ce projet est entièrement **HTML/CSS/JavaScript**, fonctionne dans tout navigateur moderne et ne nécessite aucun serveur.

---

## Fonctionnalités principales

- Formulaire clair pour saisir réseau, masque, nombre de sous-réseaux et hôtes.  
- Calcul VLSM **exact** avec préfixe minimal pour chaque sous-réseau.  
- **Tableau coloré** des sous-réseaux avec toutes les informations.  
- **Barre graphique interactive** représentant chaque sous-réseau.  
- Alertes visuelles si les sous-réseaux dépassent la capacité du réseau principal.  
- Affichage du **total d’hôtes** demandés.  
- Export PDF et Excel directement depuis le navigateur.  
- Design moderne et responsive.

---

## Capture d’écran
![Exemple](screenshot.png)  
> Remplace `screenshot.png` par une capture d’écran de ton calculateur si tu veux.

---

## Utilisation

1. Ouvrir le fichier `index.html` dans n’importe quel navigateur moderne (Chrome, Firefox, Edge, Safari).  
2. Saisir :  
   - L’adresse réseau (ex: `192.18.1.0`)  
   - Le masque (ex: `/24` ou `255.255.255.0`)  
   - Le nombre de sous-réseaux et le nombre d’hôtes par sous-réseau.  
3. Cliquer sur **Valider** pour générer les champs hôtes.  
4. Cliquer sur **Calculer** pour générer le tableau et la barre graphique.  
5. Exporter en PDF ou Excel si nécessaire.  

---

## Lien en ligne

Le calculateur peut être hébergé sur **GitHub Pages**. Après avoir ajouté le fichier `index.html` au repository et activé GitHub Pages, le site sera accessible via :  
