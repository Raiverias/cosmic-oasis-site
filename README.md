# cosmic-oasis-site

Публичная страница политики конфиденциальности игры **Cosmic Oasis**
(`com.cosmicoasis.game`, RuStore).

- Живая страница: https://raiverias.github.io/cosmic-oasis-site/
- Источник правды для контента политики — в основном (приватном) репозитории
  игры: `docs/privacy/index.html`. Изменения в политике делаются там и
  сюда копируется `index.html`.

```powershell
Copy-Item ..\CosmicOasis2\docs\privacy\index.html index.html
git commit -am "privacy: sync content"
git push
```

Ветки GitHub Pages: branch `main`, folder `/ (root)` — включается в
Settings → Pages достаточно один раз.
