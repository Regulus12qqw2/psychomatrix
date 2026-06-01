# Easy-Opencode 3.0 🚀

**9-pack hybrid super-pack for OpenCode** — ECC + gstack + ui-ux-pro-max + caveman + get-shit-done-redux + impeccable + cybersecurity + cli-anything.

Автономная AI-разработка: от идеи до готового продукта без участия человека.

## Что нового в 3.0

| Фича | v2.0 | v3.0 |
|------|------|------|
| `/run` autonomous mode | ❌ | ✅ |
| @runner agent | ❌ | ✅ |
| Impeccable design | ❌ | ✅ |
| Cybersecurity | ❌ | ✅ (top-50) |
| CLI-Anything | ❌ | ✅ (80+) |
| Skill packs | 6 | 9 |
| Skills count | 90+ | 120+ |

## Что внутри

| Компонент | Источник | Что даёт |
|-----------|----------|----------|
| **ECC** | 232+ skills | TDD, architecture, security, code review |
| **gstack** | 56+ skills | Browser QA, ship pipeline, CEO/eng review |
| **ui-ux-pro-max** | 7 skills | Топовый UI/UX, дизайн-системы |
| **caveman** | 7 skills | ~75% экономия токенов |
| **get-shit-done-redux** | 91 workflows | Spec-driven разработка |
| **impeccable** | 20+ commands | Премиальный дизайн (OKLCH, motion, anti-slop) |
| **cybersecurity** | top-50 | OWASP, API, container, secrets security |
| **cli-anything** | 80+ CLIs | Database, containers, git, build tools |

## Особенности

- **`/run` Autonomous Mode** — полный цикл: idea → research → design → build → test → qa → security → ship. Без участия человека
- **@runner agent** — автономный product builder с 11 фазами
- **Depth=1 guard** — @build единственный диспетчер. Циклы исключены
- **Caveman Adaptive** — лаконично по умолчанию, расширяется для security
- **Impeccable Design** — премиальный UI/UX без "AI-сгенерированного" вида
- **Cybersecurity** — автоматическая проверка безопасности
- **9 агентов** — @build, @runner, @planner, @architect, @designer, @reviewer, @tester, @deployer, @investigator
- **11 команд** — /run /plan /tdd /design /review /ship /qa /investigate /fast /caveman /help
- **9 MCP серверов** — Playwright, Git, Filesystem, Memory, Fetch, GitHub, Docker, SQLite, Brave Search

## Установка

```
# 1. Скопируй .opencode/ в корень проекта
# 2. Скажи агенту: "установи Easy-Opencode 3.0"
# 3. Агент сам всё настроит
```

## Быстрый старт

- **`/run [идея]`** — полный автономный цикл (НОВОЕ!)
- `/plan` — новый проект или сложная фича
- `/design` — UI/UX дизайн (impeccable)
- `/tdd` — TDD цикл (test→code→refactor)
- `/review` — код-ревью + security
- `/qa` — браузерное QA
- `/ship` — релиз
- `/fast` — быстрая правка

## /run — Autonomous Mode

Команда `/run` запускает полный автономный цикл:

```
/run создай лендинг для стартапа
```

**11 фаз:**
1. Research — анализ рынка
2. Discuss — уточнение (если нужно)
3. Spec — спецификация
4. Design — UI/UX (impeccable)
5. Plan — план
6. Build — реализация
7. Test — тесты (80%+ coverage)
8. QA — браузерное тестирование
9. Security — проверка безопасности
10. Verify — финальная верификация
11. Ship — коммит + результат

## Структура .opencode/

```
.opencode/
├── agents/          ← 9 агентов (включая @runner)
├── commands/        ← 11 команд (включая /run)
├── hooks/           ← 5 хуков (включая run-autopilot)
├── rules/           ← 5 правил (включая run-rules)
├── skills/          ← 9 паков (120+ навыков)
│   ├── ecc-core/
│   ├── gstack-core/
│   ├── caveman/
│   ├── ui-ux-pro-max/
│   ├── open-design/
│   ├── gsd-workflows/
│   ├── impeccable/      ← НОВЫЙ
│   ├── cybersecurity/   ← НОВЫЙ
│   └── cli-anything/    ← НОВЫЙ
├── installer/       ← Self-installer
├── plans/           ← Папка для планов
├── settings.jsonc   ← Конфигурация
└── AGENTS.md        ← Master-документация
```

## License

MIT
