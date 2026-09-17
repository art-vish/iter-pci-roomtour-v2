# ITER PCI Room Tour V2

Новый 3D-румтур ITER PCI. Пока опубликована стартовая страница.

- Сайт: https://art-vish.github.io/iter-pci-roomtour-v2/
- Репозиторий: https://github.com/art-vish/iter-pci-roomtour-v2
- Предыдущая версия: https://art-vish.github.io/iter-pci-roomtour/

## Публикация

GitHub Pages публикует ветку `main`, папку `/` (корень). Изменения в `main` автоматически запускают публикацию.

1. Замените `index.html` готовым румтуром.
2. Добавьте рядом необходимые JS, CSS, панорамы, текстуры и модели (например, в `assets/`).
3. Сохраните `.nojekyll` в корне.
4. Выполните commit и push в `main` и дождитесь успешного `pages build and deployment` в Actions.

Используйте относительные пути (`./assets/...`). Если сборщик требует base path, задайте `/iter-pci-roomtour-v2/`. Загружайте готовую статическую сборку; серверная часть на Pages не запускается.

Исходный репозиторий `art-vish/iter-pci-roomtour` сохраняется отдельно. Новые рендеры и новый тур публикуйте только в V2.