<p align="center"><b>◢ KENTAVR</b></p>

<p align="center">Генератор сетів і аналізатор бібліотеки для hard / industrial techno · Windows</p>

<p align="center"><b><a href="https://github.com/Hester1337/KENTAVR-PUBLIC/raw/download/KENTAVR_Setup.exe">⬇ Завантажити для Windows</a></b> · <a href="#english">English</a></p>

![Бібліотека](docs/screens/uk/1_library.jpg)

KENTAVR читає твою музичну бібліотеку, розбирає кожен трек і складає з неї сет з переходами: які треки, в якому порядку, де і як зводити. Аудіо він не генерує. Усе працює на твоєму комп'ютері, музика нікуди не завантажується.

## Що вміє

- **Аналіз треків.** Темп і сітка тактів, тональність за колом Camelot, дропи, фрази по 16/32 такти, інтро й аутро, гучність, вокал. Окремо: жорсткість і енергія за фізикою бочки і «рух» — наскільки трек качає людей. Сітку, BPM і хот-кю з Serato бере прямо з тегів файлів.
- **Генератор сетів.** Малюєш дугу енергії мишкою або береш пресет, задаєш довжину, BPM і тональність. Програма будує весь сет одразу й оцінює кожен перехід, пропонує до 3 варіантів. Треки можна замикати, міняти на кращих кандидатів і перегенеровувати решту.
- **Переходи як на пульті.** Для кожного шва: тип (LONG BLEND, BASS SWAP, DROP SLAM, ECHO OUT, HARD CUT), такт виходу і входу, план мікшера по тактах. Перехід можна одразу прослухати, бочки підігнані одна до одної.
- **Карта звучання.** Уся бібліотека розкладена за схожістю: схожі треки поруч. Виділив ділянку — отримав сет із неї.
- **Вчиться твого вуха.** Кольори жорсткості (імпорт із Serato одним кліком), правки дропів, 👍 / 👎 на переходах, записи чужих міксів. Там, де не впевнений, програма сама питає.
- **Digger.** Посилання на профіль SoundCloud, плейлист чи пошук: треки аналізуються як твої, і програма показує, що пасує саме до твоєї бібліотеки. Аудіо одразу видаляється.
- **Експорт.** Крейт прямо в Serato, Rekordbox XML з хот-кю на дропах, M3U8, CSV, TXT-трекліст, нумерація треків у тегах.
- **Інтерфейс** українською та англійською, масштаб 90–150%.

| | |
|---|---|
| ![Інспектор треку](docs/screens/uk/2_inspector.jpg) | ![Карта звучання](docs/screens/uk/3_map.jpg) |
| ![Генератор сетів](docs/screens/uk/4_set.jpg) | ![Переходи](docs/screens/uk/5_transitions.jpg) |

![Навчання](docs/screens/uk/6_learning.jpg)

## Встановлення

1. Завантаж [`KENTAVR_Setup.exe`](https://github.com/Hester1337/KENTAVR-PUBLIC/raw/download/KENTAVR_Setup.exe) і запусти.
2. Обери **Повну** (з нейромережами для точної сітки, AI-вуха і вокалу) або **Легку** версію. Права адміністратора не потрібні.
3. Ярлик з'явиться на робочому столі. Нові версії ставляться кнопкою **«Оновити»** прямо в програмі. Бібліотека й налаштування при цьому лишаються.

Якщо Windows покаже «Windows захистив ваш ПК», натисни «Докладніше» → «Усе одно запустити». Інсталятор поки не має цифрового підпису.

**Потрібно:** Windows 10 або 11 (64-біт), інтернет під час встановлення. Повна версія: ~3.5 ГБ на диску, від 8 ГБ оперативної пам'яті. Легка: ~1.2 ГБ. Відеокарта NVIDIA необов'язкова, з нею аналіз швидший.

## Приватність

- Музика, назви файлів і шляхи не покидають твій комп'ютер. Реєстрація не потрібна.
- При першому запуску програма питає, чи можна надсилати анонімну статистику роботи та мітки для навчання спільної моделі. Мітки йдуть разом із числами аналізу, без аудіо. Обидва пункти вимикаються в налаштуваннях.

## Для кого

Для діджеїв, які хочуть зрозуміти, як складається сет: чому треки пасують, де зводити і що відбувається на пульті. Згенерований сет — відправна точка, яку можна розібрати, змінити і зробити своїм. Читати зал і відчувати момент лишається за тобою.

---

<a id="english"></a>

<p align="center"><b>◢ KENTAVR</b> — a set builder and library analyser for hard / industrial techno · Windows</p>

<p align="center"><b><a href="https://github.com/Hester1337/KENTAVR-PUBLIC/raw/download/KENTAVR_Setup.exe">⬇ Download for Windows</a></b></p>

![Library](docs/screens/en/1_library.jpg)

KENTAVR reads your music library, takes every track apart and builds a set from it, transitions included: which tracks, in what order, where and how to mix. It does not generate audio. Everything runs on your computer and your music is never uploaded.

## What it does

- **Track analysis.** Tempo and beat grid, key on the Camelot wheel, drops, 16/32-bar phrases, intro and outro, loudness, vocals. Hardness and energy from the kick's physics, and "groove": how hard a track moves people. It reads Serato's grid, BPM and hot cues straight from the file tags.
- **Set generator.** Draw the energy arc with the mouse or pick a preset, set the length, BPM and key. It builds the whole set at once and scores every transition, with up to 3 versions. Lock tracks, swap them for the best candidates, regenerate the rest.
- **Transitions like on a mixer.** For every seam: the type (LONG BLEND, BASS SWAP, DROP SLAM, ECHO OUT, HARD CUT), the bars out and in, a bar-by-bar mixer plan. Listen to the transition right away, kicks locked together.
- **Sound map.** The whole library laid out by similarity, similar tracks side by side. Select an area and get a set from it.
- **It learns your ear.** Hardness colours (one-click import from Serato), drop fixes, 👍 / 👎 on transitions, recordings of other DJs' mixes. Where it is unsure, it asks.
- **Digger.** A SoundCloud profile, playlist or search: the tracks are analysed like yours, and it shows what fits your library. The audio is deleted right away.
- **Export.** A crate straight into Serato, Rekordbox XML with hot cues on the drops, M3U8, CSV, a TXT tracklist, track numbering in the tags.
- **Interface** in Ukrainian and English, 90–150% scale.

| | |
|---|---|
| ![Track inspector](docs/screens/en/2_inspector.jpg) | ![Sound map](docs/screens/en/3_map.jpg) |
| ![Set generator](docs/screens/en/4_set.jpg) | ![Transitions](docs/screens/en/5_transitions.jpg) |

![Learning](docs/screens/en/6_learning.jpg)

## Install

1. Download [`KENTAVR_Setup.exe`](https://github.com/Hester1337/KENTAVR-PUBLIC/raw/download/KENTAVR_Setup.exe) and run it.
2. Pick **Full** (with the neural nets for a precise grid, the AI ear and vocals) or **Lite**. No admin rights needed.
3. A shortcut appears on the desktop. New versions install with the **Update** button inside the program. Your library and settings stay.

If Windows says "Windows protected your PC", click "More info" → "Run anyway". The installer is not code-signed yet.

**Needs:** Windows 10 or 11 (64-bit), internet during the install. Full: ~3.5 GB of disk, 8 GB of RAM or more. Lite: ~1.2 GB. An NVIDIA GPU is optional and makes the analysis faster.

## Privacy

- Your music, file names and paths never leave your computer. No account needed.
- At the first start it asks whether it may send anonymous usage statistics and labels for training the shared model. Labels go with the analysis numbers, never the audio. Both switch off in the settings.

## Who it is for

For DJs who want to understand how a set comes together: why tracks fit, where to mix and what happens on the mixer. A generated set is a starting point to take apart, change and make your own. Reading the room and feeling the moment stay with you.

---

© Hester1337. Free for personal use. See [LICENSE](LICENSE).
