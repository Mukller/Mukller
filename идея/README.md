# идея — parked assets

Elements that were on the profile README at some point and are **kept here, but no longer rendered**.
Nothing in this folder runs: GitHub Actions only executes workflows located in `.github/workflows/`,
so moving a workflow here also stops its generation.

| Файл | Что это | Почему убран |
|---|---|---|
| `game.gif` | «GitHub Space Shooter» — гифка из репозитория `VishuChavan/Profile-Games` | визуальный шум, не несёт смысла о работе |
| `snk.yml` | воркфло, генерирующий анимированную «змейку» активности (`output`-branch) | тяжёлый фон, мешает читать текст |
| `space-shooter.yml` | воркфло, генерирующее `game.gif` | удалено вместе с самой гифкой |

## Как вернуть

1. Перенести нужный `.yml` обратно в `.github/workflows/`.
2. Вернуть картинку в корень репозитория.
3. В `README.md` добавить соответствующий `<img>` / `<picture>` блок.

> Если возвращать не планируется — репозиторий можно почистить: 2.2 МБ в `game.gif` это примерно
> 97 % размера репозитория.