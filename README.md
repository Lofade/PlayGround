# PlayGround

<!-- omgithub:readme:start -->
## 🚀 Build, play, and remix with OMGithub

**Created using [OMGithub.com](https://go.ondev.store/).**

[![OMGithub](https://img.shields.io/badge/OMGithub-Open%20project-orange?style=for-the-badge)](https://go.ondev.store/Lofade/PlayGround)
[![GitHub](https://img.shields.io/badge/GitHub-Source-181717?logo=github&style=for-the-badge)](https://github.com/Lofade/PlayGround)

- 🎮 [Open the project](https://go.ondev.store/Lofade/PlayGround).
- ✨ [Remix this project](https://go.ondev.store/Lofade/PlayGround?remix=1).
- 💻 [Explore the source](https://github.com/Lofade/PlayGround).
- 🛠️ [Check build runs](https://github.com/Lofade/PlayGround/actions).
- 🐛 [Report an issue](https://github.com/Lofade/PlayGround/issues).
- 👤 [Explore the creator's projects](https://go.ondev.store/Lofade).
- 🌍 [Create with OMGithub](https://go.ondev.store/).
<!-- omgithub:readme:end -->

## СЕРАЯ ЗОНА — выживание в Чернобыльской зоне

Автономная top-down Canvas-игра о вылазке из лагеря в Зону: исследуй сектора, ищи припасы, следи за здоровьем и запасами, переживай встречи с мутантами и враждебными группировками и возвращайся домой с добычей. Игра работает в браузере без сборки и внешних игровых библиотек.

### Запуск

Запусти любой статический веб-сервер в папке проекта. Например, через Python:

```sh
python3 -m http.server 8000
```

Открой <http://localhost:8000>. Сборка и установка зависимостей не нужны.

### Управление

- **WASD** или **стрелки** — движение; **Shift** — бег
- **Мышь** — прицеливание; **ЛКМ** — огонь; **R** — перезарядка
- **E** — взаимодействие с тайником, персонажем, артефактом или переходом между секторами
- **1–4** — выбор оружия или предмета; **I** — открыть рюкзак
- **P** или **Esc** — пауза
- **Сенсорный экран** — левый стик для движения, правый для прицеливания; экранные кнопки — стрельба, действие, бег и использование предметов.

Проверь припасы перед выходом, исследуй отмеченные сектора и возвращайся в Скадовск. Находки и расходники помогают пережить следующую вылазку.

### Лицензии игровых моделей

Использованные модели и сведения об их авторах приведены ниже; исходные GLB-файлы и метаданные атрибуции находятся в `public/models/`. Активы по **CC BY-NC** допустимо использовать без отдельного разрешения только в некоммерческих целях и при соблюдении условий лицензии, включая атрибуцию. Для коммерческого распространения такого актива требуется отдельное разрешение правообладателя либо замена модели на актив с подходящей лицензией.

### 3D model credits

The in-game character, barracks, and pine-tree sprites are rendered from these Sketchfab models. The source GLB files and their attribution metadata are included in `public/models/`.

- **A.B.C. Soldier (low poly)** by [Götz von Berlichingen](https://sketchfab.com/vonBerlichingen) — [Sketchfab model](https://sketchfab.com/3d-models/abc-soldier-low-poly-813f1b7ea16b41b79c8b9378516e5dc6)
- **Hut - Barracks Package / Low Poly - Game Ready** by [Renend Studio](https://sketchfab.com/RenendStudio) — [Sketchfab model](https://sketchfab.com/3d-models/hut-barracks-package-low-poly-game-ready-746cd3525d0d419cbbb02891da9a2d1b)
- **Low Poly Pine Trees** by [luka712](https://sketchfab.com/luka712) — [Sketchfab model](https://sketchfab.com/3d-models/low-poly-pine-trees-46c3811b9a9445cdb2ff3e663d1f2c11)

All three models are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). The sprites are rendered adaptations of the models for this game's Canvas renderer.
