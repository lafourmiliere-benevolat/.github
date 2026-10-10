# La Fourmilière — configuration GitHub

Ce dépôt public contient les éléments partagés de l’organisation GitHub et son
profil public.

## Profil de l’organisation

[`profile/README.md`](profile/README.md) est affiché sur la page
[github.com/lafourmiliere-benevolat](https://github.com/lafourmiliere-benevolat).
Gardez son contenu court, accueillant, vérifiable et utile aux personnes qui
veulent découvrir l’association ou contribuer.

## Fichiers communautaires par défaut

GitHub peut utiliser les fichiers communautaires pris en charge dans ce dépôt
pour les dépôts de l’organisation qui n’ont pas leur propre version :

- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) — code de conduite
- [`FUNDING.yml`](FUNDING.yml) — lien de soutien financier

GitHub donne priorité au fichier propre au dépôt concerné. La liste des types
pris en charge et les règles de priorité sont documentées dans la
[documentation GitHub sur les fichiers communautaires par défaut](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

## Configuration locale à ce dépôt

- [`.github/CODEOWNERS`](.github/CODEOWNERS) s’applique uniquement à ce dépôt ; GitHub ne propage pas les CODEOWNERS depuis le dépôt d’organisation.
- [`cliff.toml`](cliff.toml) est la configuration de référence pour git-cliff, mais GitHub ne la distribue pas aux autres dépôts. Les projets qui l’utilisent doivent la copier ou la synchroniser explicitement.
- [`renovate.json`](renovate.json) configure Renovate pour ce dépôt.
- [`.github/workflows/metrics.yml`](.github/workflows/metrics.yml) est l’automatisation historique de la carte Metrics. Son SVG n’est plus affiché sur le profil tant que l’automatisation n’a pas été remise en état et que l’image n’a pas été actualisée.

## Dépôts publics

- [renovate-config](https://github.com/lafourmiliere-benevolat/renovate-config) — configuration Renovate partagée
- [capistrano-good_job](https://github.com/lafourmiliere-benevolat/capistrano-good_job) — intégration systemd de GoodJob pour Capistrano (archivé)
- [.github](https://github.com/lafourmiliere-benevolat/.github) — ce dépôt
