# Link Cord i18n
Localization files for the Link Cord Website.

---

## Supported Languages
- English
- Spansih

---

## File Structure
```
# Base Files
└── i18n.config.js

# Locale Types
 ├── i18n
  └── index.tsx
  
# Locales Directory
 ├── locales
  ├── English
   └── English.tsx
  ├── Spanish
   └── Spanish.tsx
```

---

## Contributing 
- Submit a PR (Pull Request) with your Changes/Lang Files
- Please follow the layout provided on [types](./i18n/index.tsx)
- The layout interface should be implemented/imported into the locale files see [en-US](./i18n/en-US.tsx) for an example
- Make sure you add any new Lang's to the the Config File 👌🏻
- Variables such as `username` etc can be called using `{{locale_var}}`

---

## License
- All rights reserved! 
