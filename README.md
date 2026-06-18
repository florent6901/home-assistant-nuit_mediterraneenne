# 🌊 Mediterranean Night

> Theme for [Home Assistant](https://www.home-assistant.io/)

[![](https://img.shields.io/badge/My-Configuration-blue?style=for-the-badge)](https://github.com/florent6901/home-assistant-nuit_mediterraneenne) [![hacs_badge](https://img.shields.io/badge/HACS-Custom%20Repository-orange.svg?style=for-the-badge)](https://github.com/hacs/integration) 

---

## 🎨 Theme preview

- **Mediterranean Night**

<img width="1018" height="895" alt="preview" src="https://github.com/user-attachments/assets/ceb99be8-20fc-4ad1-a45f-f3e7b392b291" />

- **Mediterranean Night Dark**

<img width="895" height="893" alt="preview_dark" src="https://github.com/user-attachments/assets/18fbcae8-6073-465b-b5f4-5ac4165fd673" />

- **Mediterranean Night Halo**

<img width="901" height="894" alt="preview_halo" src="https://github.com/user-attachments/assets/93fc550d-cb83-48de-b5e8-f428fa19f8bc" />

- **Mediterranean Night Silver**

<img width="900" height="891" alt="preview_sylver" src="https://github.com/user-attachments/assets/b8b328e0-ca15-4aaf-9e31-be36f6b65edc" />

---

## 📦 Installation via HACS

> 💡 Currently available as a **custom repository**.  
> Submission to the official HACS store is in progress.

1. Open **HACS** in Home Assistant
2. Go to → **Menu → Custom repositories**
3. Paste the URL of this repository and select the **Theme** category
4. Click **Add**, then install **Mediterranean Night**
5. All **4 variants** are available under **Profile → Theme**

---

## 🔧 Manual installation

1. Copy the contents of the `themes/` folder into the `config/themes/nuit-mediterraneenne/` folder
2. Add the following line to your `configuration.yaml` file:

```yaml
frontend:
  themes: !include_dir_merge_named themes
```

3. Reload the Home Assistant YAML configuration
4. Go to **Profile** → **Theme** → **All 4 variants will be available**

---

## 🗂️ Repository structure

```
nuit-mediterraneenne/
├── themes/
│   └── Nuit Mediterraneenne.yaml
│   └── Nuit Mediterraneenne Silver.yaml
│   └── Nuit Mediterraneenne Halo.yaml
│   └── nuit_mediterraneenne_background.png
│   └── Nuit Mediterraneenne Dark.yaml
├── hacs.json
├── README.md
├── LICENSE
```

---

## 🤝 Contributing

If you have suggestions for improvements or bugs to report, feel free to reach out.

Thank you for your support.