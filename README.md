# Duckify 🦆

**Décodeur Canard ↔ Français**

Vous rêvez de parler tel un canard ? Vous voulez communiquer en `coin` et en `quack` tout en restant compréhensible ?  
Duckify est fait pour vous !

Duckify est un ensemble de scripts Python qui vous permet :

- d’**encoder** n’importe quel texte en un « langage canardisé » (jetons canard ↔ hex → zlib)  
- de **décoder** un document canardisé en français structuré par chapitres  

---

## 🚀 Fonctionnalités

- **Bijection Duck ↔ HEX** (un mot-canard par caractère hexadécimal)  
- **Compression zlib** avant encodage pour garantir intégrité et compacité  
- **Décodage mot à mot** avec gestion des erreurs de jetons  
- **Structure des chapitres** reconnue (`I. …`, `II. …`, …) et restituée à l’identique  

---
