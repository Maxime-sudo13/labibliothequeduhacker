# ⌁ La Bibliothèque du Hacker

**La référence interactive de l'arsenal Kali Linux**, rangée par phase d'intrusion — pour apprendre la cybersécurité.

🔗 **Site en ligne :** https://maxime-sudo13.github.io/labibliothequeduhacker/

![outils](https://img.shields.io/badge/outils-176-00ff9c) ![commandes](https://img.shields.io/badge/commandes-834-00e5ff) ![catégories](https://img.shields.io/badge/cat%C3%A9gories-16-9d7bff)

---

## Qu'est-ce que c'est ?

Une page web **autonome** (un seul fichier `index.html`, aucune dépendance) qui référence **176 outils** de pentest et **834 commandes**, classés en **16 catégories** suivant les étapes d'un test d'intrusion : reconnaissance → scan → énumération web → failles → exploitation → mots de passe → WiFi → MITM → Active Directory → cloud → forensics → reverse → mobile → social → anonymat.

### Fonctionnalités

- 🔎 **Recherche instantanée** (nom, rôle, commande) + raccourci clavier `/`
- 🗂️ **Filtre par catégorie** (barre latérale sur ordinateur, barre défilable sur mobile)
- 🪟 **Fiche détaillée par outil** : toutes ses commandes, **copiables en 1 clic**, + bouton « Copier tout »
- ⭐ **Favoris** (sauvegardés dans le navigateur)
- 📦 **Commande d'installation** sur chaque fiche (défaut Kali ou `apt`/`pipx`/`go`…)
- ↗️ **Lien vers le dépôt / la doc officielle** de chaque outil
- 📖 **Référence complète** : `man <outil>` / `<outil> --help` pour la liste exhaustive des options
- 🌙 Thème sombre « cyber », responsive mobile

## Utilisation

Ouvre simplement le [site en ligne](https://maxime-sudo13.github.io/labibliothequeduhacker/), ou clone le repo et ouvre `index.html` dans ton navigateur :

```bash
git clone https://github.com/Maxime-sudo13/labibliothequeduhacker
cd labibliothequeduhacker
xdg-open index.html   # ou ouvre le fichier à la main
```

## ⚠️ Avertissement légal

Ces outils s'emploient **uniquement** sur ta propre infrastructure ou avec une **autorisation écrite**. Les lancer contre un système tiers sans mandat est un **délit** (en France : articles 323-1 et suivants du code pénal).

Cette ressource est **éducative et défensive**. Entraîne-toi légalement sur **tes machines** ou des labs dédiés : [HackTheBox](https://www.hackthebox.com/), [TryHackMe](https://tryhackme.com/), Metasploitable, DVWA.

Les auteurs et contributeurs déclinent toute responsabilité en cas d'usage illégal.

---

*Les statuts « défaut / à installer » correspondent au métapaquet `kali-linux-default`. Les noms, descriptions et liens sont fournis à titre indicatif.*
