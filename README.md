# 🌊 Nuit Méditerranéenne

> Thème bleu sombre pour [Home Assistant](https://www.home-assistant.io/)

[![](https://img.shields.io/badge/My-Configuration-blue?style=for-the-badge)](https://github.com/florent6901/home-assistant-nuit_mediterraneenne)
[![hacs_badge](https://img.shields.io/badge/HACS-Custom%20Repository-orange.svg?style=for-the-badge)](https://github.com/hacs/integration)
![HA Version](https://img.shields.io/badge/Home%20Assistant-2026.02%2B-38BDF8?style=for-the-badge&logo=home-assistant&logoColor=white)

---
## 🎨 Aperçu du thème

- **Nuit Méditerranéenne**

![Apercu](<img width="1018" height="895" alt="preview" src="https://github.com/user-attachments/assets/cb60fe8d-43b3-40a8-b0b9-1754af1bbba9" />)


- **Nuit Méditerranéenne Dark**

![Apercu_Dark](<img width="895" height="893" alt="preview_dark" src="https://github.com/user-attachments/assets/addc4973-02f0-4359-aed1-47bef7a78b8a" />
)

- **Nuit Méditerranéenne Halo**

![Apercu_Halo](<img width="901" height="894" alt="preview_halo" src="https://github.com/user-attachments/assets/79498c86-ef4b-4203-9b3d-afa48f28668b" />
)

- **Nuit Méditerranéenne Sylver**

![Apercu_Sylver](<img width="900" height="891" alt="preview_sylver" src="https://github.com/user-attachments/assets/725abc0f-cd65-4b02-974e-f7b1bdbcb3a1" />
)

---
## 📦 Installation via HACS

> 💡 Actuellement disponible en **dépôt personnalisé**. > Soumission au store officiel HACS en cours.

1. Ouvrir **HACS** dans Home Assistant
2. Aller dans **Thèmes** → menu ⋮ → **Dépôts personnalisés**
3. Coller l'URL de ce dépôt et sélectionner la catégorie **Thème**
4. Cliquer sur **Ajouter**, puis installer **Nuit Méditerranéenne**
5. Les **4 variantes** sont disponibles dans **Profil → Thème**

---
## 🔧 Installation manuelle

1. Copier le dossier `themes/` dans le dossier `config/themes/`
2. Copier le dossier `www/` dans le dossier `config/www/`
3. Ajouter la ligne dans le fichier `configuration.yaml` :

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
│   └── nuit_mediterraneenne.yaml
│   └── nuit_mediterraneenne_silver.yaml
│   └── nuit_mediterraneenne_halo.yaml
│   └── nuit_mediterraneenne_background.png
│   └── nuit_mediterraneenne_dark.yaml
├── hacs.json
├── README.md
```

---
## 📋 Changelog

### v1.0.0

- Version initiale — 4 variantes incluses
- Compatibilité Home Assistant 2026.02+

---
## 🤝 Contribution

Si vous avez des suggestions d'amélioration ou des bugs à signaler, n'hésitez pas.
