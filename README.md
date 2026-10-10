# Undertale FR Patcher — Undertale Yellow & Red and Yellow FR

Patcher de traduction française autonome et multiplateforme pour **Undertale Yellow** et **Undertale Red & Yellow**.

> Développé par **Cronos** & **Anthan**  
> Portail officiel : [undertale-fr.cronos.build](https://undertale-fr.cronos.build)

---

## 🎮 Fonctionnalités

- **Moteur Rust Léger & Robuste** : Interface graphique fluide construite avec `egui` et backend CPU logiciel (aucun GPU requis, compatibilité totale avec Wine, Proton et Steam Deck).
- **Détection Automatique du Jeu** : Détection instantanée des répertoires d'installation Steam (Linux, SteamOS, Windows).
- **Application xdelta3 Non-Destructive** : Application directe des patchs binaires sans altérer vos sauvegardes existantes ni nécessiter de manipulation complexe.
- **Vérification d'Intégrité Cryptographique** : Contrôle systématique des sommes de contrôle SHA-256 avant et après application du patch.
- **Gestion des Raccourcis & Lanceurs** : Création automatique des entrées `.desktop` sur Linux et des raccourcis de bureau.

---

## 📦 Contenu du dépôt

| Fichier / Dossier | Description |
|---|---|
| `zenith-patcher-rs/` | Code source du patcher en Rust (`egui`, `softbuffer`, `minreq`, `sha2`) |
| `versions.json` | Métadonnées de versions et hachages SHA-256 lus par le patcher |
| `patches/` | Fichiers de patch delta légers |

---

## 🛠️ Compilation depuis les sources

Prérequis : [Rust & Cargo](https://rustup.rs/) (édition 2021+).

```bash
cd zenith-patcher-rs
cargo build --release
```

Le binaire optimisé sera généré dans `target/release/undertale-fr-patcher`.

---

## 🔗 Liens & Ressources

- **Site Web Officiel** : [https://undertale-fr.cronos.build](https://undertale-fr.cronos.build)
- **Portfolio Développeur** : [https://cronos.build](https://cronos.build)
- **Communauté Discord** : [https://discord.gg/mAwZBxhSSf](https://discord.gg/mAwZBxhSSf)
