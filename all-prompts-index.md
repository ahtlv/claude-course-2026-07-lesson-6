# Всё, что было на курсе — указатель

> Шпаргалка на будущее. Через месяц вы вспомните, что «был промпт про защиту файлов», но не
> вспомните, в каком из шести репозиториев он лежал. Здесь всё в одной таблице.
>
> Все ссылки проверены и ведут в публичные репозитории курса.

---

## 🎯 Промпты по порядку

Нумерация сквозная через весь курс — она не совпадает с номерами занятий, потому что часть
промптов писалась и переставлялась по ходу.

| № | Промпт | Что делает | Занятие |
|---|---|---|---|
| 00 | [Забери своего персонажа](https://github.com/ahtlv/claude-course-2026-07-lesson-1/blob/main/prompts/00-get-character.md) | Агент сам скачивает папку персонажа из репозитория — первое «вау», ноль команд в терминале | 1 |
| 01 | [About-страница](https://github.com/ahtlv/claude-course-2026-07-lesson-1/blob/main/prompts/01-about-page.md) | Первый артефакт: страница о себе, открывается в браузере | 1 |
| 02 | [Матч контекста с рынком](https://github.com/ahtlv/claude-course-2026-07-lesson-3/blob/main/prompts/02-yc-match.md) | Агент сопоставляет ваш профиль с запросами Y Combinator и предлагает идеи под вас | 3 |
| 03 | [Лендинг вашей идеи](https://github.com/ahtlv/claude-course-2026-07-lesson-4/blob/main/prompts/03-startup-landing.md) | Второй артефакт: страница про вашу идею | 4 |
| 04 | [Контекст-профиль](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/prompts/04-context-profile.md) | Кто вы, чем занимаетесь, как с вами разговаривать — основа всего дальнейшего | 2 |
| 04 | [Что из идеи сделать по-настоящему](https://github.com/ahtlv/claude-course-2026-07-lesson-4/blob/main/prompts/04-mvp-options.md) | Агент предлагает варианты демо, вы выбираете один | 4 |
| 05 | [Интервью для CLAUDE.md](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/prompts/05-claude-md-interview.md) | Агент берёт у вас интервью и собирает файл контекста проекта | 2 |
| 06 | [Личный системный промпт](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/prompts/06-personal-system-prompt.md) | Глобальный `CLAUDE.md` — правила, которые действуют во всех проектах | 2 |
| 07 | [Видимая папка настроек](https://github.com/ahtlv/claude-course-2026-07-lesson-3/blob/main/prompts/07-global-config-setup.md) | `claude-config` рядом с проектами вместо скрытой системной папки | 3 |
| 08 | [Конфиг в свой GitHub](https://github.com/ahtlv/claude-course-2026-07-lesson-3/blob/main/prompts/08-claude-config-to-github.md) | Бэкап настроек и перенос между компьютерами | 3 |
| 09 | [Playwright MCP](https://github.com/ahtlv/claude-course-2026-07-lesson-3/blob/main/prompts/09-playwright-mcp.md) | Первый настоящий MCP: агент управляет реальным браузером | 3 |
| 10 | [Агент, который спорит](https://github.com/ahtlv/claude-course-2026-07-lesson-3/blob/main/prompts/10-rules-nonconformism.md) | Нонконформизм: правило, по которому агент перестаёт поддакивать | 3 |
| 16 | [Obsidian и структура PARA](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/obsidian/prompts/16-obsidian-para-setup.md) | Разворачивает базу знаний: проекты, области, ресурсы, архив | 5 |
| 17 | [Синхронизация Obsidian с GitHub](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/obsidian/prompts/17-obsidian-github-sync.md) | База знаний уезжает в репозиторий и живёт на всех устройствах | 5 |
| 18 | [Хук: звук по завершении](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/prompts/18-sound-hook.md) | Агент подаёт сигнал, когда закончил работу | 5 |
| 19 | [Своя команда `/review`](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/prompts/19-review-command.md) | Первая slash-команда: проверка страницы на адаптив, вёрстку, тексты | 5 |
| 20 | [Дизайн-система на лендинг](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/prompts/20-design-system.md) | `DESIGN.md` известного бренда поверх вашей страницы | 5 |
| 21 | [Хук: защита файлов](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/prompts/21-protect-files.md) | Агент не может тронуть `.env`, ключи и `.git/` | 5 |
| 00 | [Skill markitdown](https://github.com/ahtlv/claude-course-2026-07-lesson-6/blob/main/prompts/00-get-skill-markitdown.md) | PDF/Word/PPT/Excel/YouTube → чистый текст перед тем, как Claude их читает — экономит токены | 6 |

> ⚠️ Номера 00 и 04 встречаются дважды каждый — так сложилось при пересборке курса.
> Смотрите на занятие.

---

## ⚡ Slash-команды

Лежат в [занятии 5](https://github.com/ahtlv/claude-course-2026-07-lesson-5/tree/main/slash-commands).
Кладутся в папку `commands` рядом с настройками — глобально работают в любом проекте.

| Команда | Что делает |
|---|---|
| [`/explain`](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/slash-commands/explain.md) | Разбирает страницу по блокам с номерами строк: где менять текст, где картинку, где цвет |
| [`/backup`](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/slash-commands/backup.md) | Точка возврата перед экспериментом + готовые команды, как вернуться |
| [`/ship`](https://github.com/ahtlv/claude-course-2026-07-lesson-5/blob/main/slash-commands/ship.md) | Осмысленный коммит и публикация страницы |
| [ещё семь в папке `more/`](https://github.com/ahtlv/claude-course-2026-07-lesson-5/tree/main/slash-commands/more) | `/orient`, `/preflight`, `/texts`, `/mobile`, `/speed`, `/undo`, `/next` |

Своя команда — это просто `.md`-файл с промптом. Имя файла становится именем команды.

---

## 🤖 Субагенты

Кладутся в `~/.claude/agents/` — [занятие 4](https://github.com/ahtlv/claude-course-2026-07-lesson-4/tree/main/agents).

| Агент | Зачем |
|---|---|
| [`anthropic-docs`](https://github.com/ahtlv/claude-course-2026-07-lesson-4/blob/main/agents/anthropic-docs.md) | Отвечает на вопросы про Claude Code по официальной документации |
| [`reviewer`](https://github.com/ahtlv/claude-course-2026-07-lesson-4/blob/main/agents/reviewer.md) | Проверяет любой результат свежим взглядом, без контекста разговора |

---

## 📄 Шаблоны и справочники

| Файл | О чём | Занятие |
|---|---|---|
| [`templates/PRD.md`](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/templates/PRD.md) | Описание продукта: что делаем и как это должно работать | 2 |
| [`templates/README.md`](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/templates/README.md) | Как оформить проект, чтобы через месяц понять, что это | 2 |
| [`templates/progress.md`](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/templates/progress.md) | Журнал работы над проектом | 2 |
| [`git-workflow.md`](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/git-workflow.md) | Git по-человечески: что такое коммит, ветка, пуш | 2 |
| [`deploy-guide.md`](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/deploy-guide.md) | Публикация страницы на GitHub Pages | 2 |
| [`github-setup.md`](https://github.com/ahtlv/claude-course-2026-07-lesson-1/blob/main/github-setup.md) | Регистрация и первичная настройка GitHub | 1 |
| [`mcp-catalog.md`](https://github.com/ahtlv/claude-course-2026-07-lesson-3/blob/main/mcp-catalog.md) | Каталог MCP-серверов: что бывает и что стоит подключить | 3 |
| [`obsidian/`](https://github.com/ahtlv/claude-course-2026-07-lesson-5/tree/main/obsidian) | База знаний целиком: PARA, синк с GitHub, работа Claude Code в vault, готовый скилл | 5 |

---

## 🏆 Творческие задания

| Задание | Суть | Занятие |
|---|---|---|
| [8-битная игра](https://github.com/ahtlv/claude-course-2026-07-lesson-2/blob/main/retro-game-challenge.md) | Собрать игру в ретро-стиле и пошарить в чат | 2 |
| [Потрогай мою идею](https://github.com/ahtlv/claude-course-2026-07-lesson-4/blob/main/idea-demo-challenge.md) | Проходимое демо рядом с лендингом | 4 |
| [Заведи агенту характер](https://github.com/ahtlv/claude-course-2026-07-lesson-4/blob/main/character-skill-challenge.md) | Свой скилл, меняющий манеру агента | 4 |

---

## 📚 Репозитории занятий целиком

| Занятие | Тема | Ссылка |
|---|---|---|
| 1 | Зачем, установка, первый промпт | [lesson-1](https://github.com/ahtlv/claude-course-2026-07-lesson-1) |
| 2 | Как думать о задачах и что под капотом | [lesson-2](https://github.com/ahtlv/claude-course-2026-07-lesson-2) |
| 3 | MCP: подключение внешнего мира | [lesson-3](https://github.com/ahtlv/claude-course-2026-07-lesson-3) |
| 4 | Агенты, скиллы, `.claude/` | [lesson-4](https://github.com/ahtlv/claude-course-2026-07-lesson-4) |
| 5 | Инструменты профессионала | [lesson-5](https://github.com/ahtlv/claude-course-2026-07-lesson-5) |
| 6 | Финал: что дальше | [lesson-6](https://github.com/ahtlv/claude-course-2026-07-lesson-6) |

⚠️ **Репозитории публичные на время курса.** Хотите сохранить наверняка — скачайте нужное
себе или сделайте форк: нажмите **Fork** в правом верхнем углу репозитория, и копия
останется в вашем GitHub навсегда.

---

## 🧭 Если не помните, что искать

- **«Как мне объяснить агенту, кто я»** → промпты 04, 05, 06
- **«Агент со мной соглашается, а мне нужен спор»** → промпт 10
- **«Хочу, чтобы он сам ходил в браузер»** → промпт 09 и каталог MCP
- **«Хочу проверить, что получилось»** → промпт 19, команда `/review`
- **«Боюсь, что он сломает или выложит лишнее»** → промпт 21
- **«Куда девать все свои заметки»** → папка `obsidian/`, промпты 16–17
- **«Страница выглядит как у всех»** → промпт 20
- **«Что делать дальше, курс кончился»** → [`roadmap.md`](roadmap.md)
