# 🛡️ CyberDetect - Détecteur de Phishing (Atelier Cybersécurité)

Application web interactive et dynamique conçue pour simuler et analyser des cas réels de phishing (SMS, mails, DM Discord) lors d'ateliers de sensibilisation en milieu scolaire (collèges et lycées).

## 🌐 Accès direct à l'outil en ligne

Le site est hébergé sur GitHub Pages et accessible directement ici :  
👉 **[https://Vim-mosfet.github.io/cyberdetect/](https://Vim-mosfet.github.io/cyberdetect/)**

---

## 🎯 Principe de l'atelier

1. **Projection sur Grand Écran** : L'outil est affiché au tableau via un vidéoprojecteur.
2. **Débat & Analyse** : Les élèves observent le message affiché (expéditeur, contenu, liens, sentiment d'urgence) et débattent.
3. **Vote à main levée** : La classe vote pour déterminer si le message est **SÛR** ou s'il s'agit d'une **ARNAQUE**.
4. **Validation par l'intervenant** : L'animateur clique sur la décision retenue par la majorité pour déclencher le débriefing interactif (ou l'effet visuel de données corrompues en cas d'erreur/clic sur le piège).

---

## 📋 Scénarios inclus

L'application intègre 5 cas pratiques équilibrés et ultra-réalistes :
- ❌ **SMS Chronopost** *(Phishing - Faux domaine et urgence)*
- ✅ **SMS Snapchat** *(Légitime - Numéro court officiel 38600)*
- ❌ **DM Discord Nitro** *(Phishing - Compte ami piraté & lien en .ru)*
- ✅ **Mail ENT / Établissement** *(Légitime - Mail d'information de maintenance)*
- ❌ **Mail Epic Games / V-Bucks** *(Phishing - Faux cadeau Fortnite)*

---

## 🛠️ Stack technique

- **HTML5 / JavaScript ES6** (Single Page Application autonome)
- **Tailwind CSS** (Design sombre responsive et adapté à la projection)
- **WebAudio API** (Signaux sonores d'alerte intégrés)
