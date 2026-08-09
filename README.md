# 北陸Ruby会議02
- https://regional.rubykaigi.org/hokuriku02/

## デプロイ
- GitHub Pages
  - main ブランチに push 時に GitHub Actions でデプロイ
  - `/docs` 以下がコンテンツとして公開されます
  - https://hokurikurb.github.io/hokuriku02/
- 地域Ruby会議(`regional.rubykaigi.org`)への反映
  - GitHub Pages に反映後に自動で反映
  - 地域Ruby会議(`ruby-no-kai/rko-router`)で proxy (キャッシュ: 10min)
