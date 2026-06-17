# 🌊 Nuit Méditerranéenne

> Thème pour [Home Assistant](https://www.home-assistant.io/)

[![](https://img.shields.io/badge/My-Configuration-blue?style=for-the-badge)](https://github.com/florent6901/home-assistant-nuit_mediterraneenne)
[![hacs_badge](https://img.shields.io/badge/HACS-Custom%20Repository-orange.svg?style=for-the-badge)](https://github.com/hacs/integration)
![HA Version](https://img.shields.io/badge/Home%20Assistant-2026.02%2B-38BDF8?style=for-the-badge&logo=home-assistant&logoColor=white)

---
## 🎨 Aperçu du thème

- **Nuit Méditerranéenne**

<img width="1018" height="895" alt="preview" src="https://github.com/user-attachments/assets/ceb99be8-20fc-4ad1-a45f-f3e7b392b291" />

- **Nuit Méditerranéenne Dark**

<img width="895" height="893" alt="preview_dark" src="https://github.com/user-attachments/assets/18fbcae8-6073-465b-b5f4-5ac4165fd673" />

- **Nuit Méditerranéenne Halo**

<img width="901" height="894" alt="preview_halo" src="https://github.com/user-attachments/assets/93fc550d-cb83-48de-b5e8-f428fa19f8bc" />

- **Nuit Méditerranéenne Silver**

<img width="900" height="891" alt="preview_sylver" src="https://github.com/user-attachments/assets/b8b328e0-ca15-4aaf-9e31-be36f6b65edc" />

---
## 📦 Installation via HACS

> 💡 Actuellement disponible en **dépôt personnalisé**. > Soumission au store officiel HACS en cours.

1. Ouvrir **HACS** dans Home Assistant
2. Aller dans → **Menu → **Dépôts personnalisés**
3. Coller l'URL de ce dépôt et sélectionner la catégorie **Thème**
4. Cliquer sur **Ajouter**, puis installer **Nuit Méditerranéenne**
5. Les **4 variantes** sont disponibles dans **Profil → Thème**

---
## 🔧 Installation manuelle

1. Copier le contenu du dossier `themes/` dans le dossier `config/themes/nuit-mediterraneenne/`
2. Ajouter la ligne dans le fichier `configuration.yaml` :

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. Recharger la configuration YAML de Home Assistant
4. Aller dans **Profil** → **Thème** → **Les 4 variantes seront présentes**

---

## 🗂️ Structure du dépôt

```
nuit-mediterraneenne/
├── themes/
│   └── Nuit Mediterraneenne.yaml
│   └── Nuit Mediterraneenne Silver.yaml
│   └── Nuit Mediterraneenne Halo.yaml
│   └── Nuit Mediterraneenne Background.png
│   └── Nuit Mediterraneenne Dark.yaml
├── hacs.json
├── README.md
├── LICENSE
```

---
## 🤝 Contribution

Si vous avez des suggestions d'amélioration ou des bugs à signaler, n'hésitez pas.
Merci pour votre soutien.
