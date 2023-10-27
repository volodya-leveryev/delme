# Работа с GitHub Actions

1. Создать репозиторий в GitHub
2. Склонировать репозиторий на локальный компьютер
3. Установить [Hugo](https://gohugo.io)
4. Создать скелет нового сайта: `hugo new site --force .`
5. Добавить тему оформления:
   ```
   git submodule add --depth 1 https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke
   ```
6. Задать тему в конфигурационном файле `hugo.toml`
7. Создать страницу `hugo new content posts/my-first-post.md`
8. Проверить работу сайта локально ``
