```
██████╗ ███████╗██████╗     ██████╗  ██████╗  ██████╗ 
██╔══██╗██╔════╝██╔══██╗    ██╔══██╗██╔═══██╗██╔════╝ 
██████╔╝█████╗  ██║  ██║    ██║  ██║██║   ██║██║  ███╗
██╔══██╗██╔══╝  ██║  ██║    ██║  ██║██║   ██║██║   ██║
██║  ██║███████╗██████╔╝    ██████╔╝╚██████╔╝╚██████╔╝
╚═╝  ╚═╝╚══════╝╚═════╝     ╚═════╝  ╚═════╝  ╚═════╝ 
```

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-red?style=for-the-badge)
![Python](https://img.shields.io/badge/python-3.10+-blue?style=for-the-badge&logo=python)
![Discord](https://img.shields.io/badge/discord-bot-7289da?style=for-the-badge&logo=discord)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

**🔴 Bot OSINT Discord — Usage éthique & légal uniquement 🔴**

</div>

---

## 🐕 Présentation

**Red Dog** est un bot OSINT open-source pour Discord.  
Il permet de rechercher des informations **publiques** sur des pseudos, adresses IP, domaines et emails.

> ⚠️ Usage légal uniquement. L'auteur décline toute responsabilité en cas d'abus.

---

## 📋 Commandes

```
[0.] help      — Affiche toutes les commandes
[1.] username  — Recherche un pseudo sur 20+ plateformes
[2.] instagram — Recherche un compte Instagram public
[3.] snapchat  — Vérifie l'existence d'un compte Snapchat
[4.] twitter   — Recherche un compte Twitter/X
[5.] tiktok    — Recherche un compte TikTok
[6.] github    — Infos sur un profil GitHub
[7.] reddit    — Recherche un compte Reddit
[8.] ip        — Géolocalisation + ASN + FAI d'une IP
[9.] domain    — WHOIS + DNS d'un domaine
[10.] email    — Vérification fuites (HaveIBeenPwned)
[11.] company  — Infos publiques sur une entreprise
```

---

## 🚀 Installation

### 1. Cloner le repo
```bash
git clone https://github.com/TON_PSEUDO/red-dog.git
cd red-dog
```

### 2. Installer les dépendances
```bash
pip install -r requirements.txt
```

### 3. Configurer le `.env`
```bash
cp .env.example .env
nano .env
```

### 4. Lancer le bot
```bash
python bot.py
```

---

## ⚙️ Configuration `.env`

```env
DISCORD_TOKEN=ton_token_ici
HIBP_API_KEY=ta_cle_hibp_ici  # optionnel
```

---

## 📁 Structure

```
red-dog/
├── bot.py
├── modules/
│   ├── social.py       # Recherche pseudo multi-plateformes
│   ├── network.py      # Analyse IP & domaine
│   ├── email_check.py  # Vérification fuites
│   └── company.py      # Recherche entreprise
├── requirements.txt
├── .env.example
└── README.md
```

---

## 🤝 Contribution

Les PR sont bienvenues ! Ouvre une issue pour proposer une nouvelle source.

---

## 📜 Licence

MIT — Libre d'utilisation avec attribution.

---

<div align="center">
Made with 🔴 by Red Dog Team
</div>
