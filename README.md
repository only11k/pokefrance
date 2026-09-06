# PokéFrance

Distribution du launcher et du modpack du serveur PokéFrance.

- `launcher/manifest.json` — la liste des fichiers du modpack, lue par le launcher au démarrage
- `launcher/pokefrance-rp.zip` — le pack de ressources envoyé par le serveur

Les fichiers du modpack eux-mêmes sont déposés dans les *releases* : une release
par version du pack, les chemins mis à plat (`mods/x.jar` devient `mods__x.jar`),
puisqu'une release ne connaît pas les sous-dossiers.
