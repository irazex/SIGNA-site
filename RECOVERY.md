# Восстановление SIGNA-site

Действующий сайт SIGNA Cafe.

## Начало работы из чистого клона

В корне выполни `npm ci` и `npm run build`, затем `php -S 127.0.0.1:8099 -t . tools/dev-router.php`. Открой главную страницу и `/stories`.

## Рабочие данные, выпуск и откат

Серверные правила Apache и PHP описаны в AGENTS. Рабочие настройки админки, загрузки и состояние хостинга восстанавливаются из копии владельца. При проверке локального сайта используй вымышленный контент.

При восстановлении действующего сервиса сверь production-ревизию в журнале выпуска с активной версией. Общий порядок описан в [регламенте восстановления](https://github.com/irazex/knowledge-hub/blob/main/reference/project-recovery.md).

## Решения и история

- [История коммитов](https://github.com/irazex/SIGNA-site/commits/main).
- [Pull requests](https://github.com/irazex/SIGNA-site/pulls?q=is%3Apr).
- [AGENTS.md](<AGENTS.md>).
- [HANDOVER.md](<HANDOVER.md>).
- [TASKS.md](<TASKS.md>).
- [deploy/RELEASE_QUEUE.md](<deploy/RELEASE_QUEUE.md>).
- [tools/dev-router.php](<tools/dev-router.php>).

## Зафиксированные решения

- 09.11.2026 — Восстановление Stories зафиксировано после проверки рабочего сайта. [Коммит 2a3f9a0](https://github.com/irazex/SIGNA-site/commit/2a3f9a0b31b7257e973d5209c3e8c887e024b9e3).

## Учебный пример

Пример карточки для тестового сайта: «Демо-завтрак», вымышленное описание, 85000 IDR.

Первичный комплект сверили с чистым клоном на [82a265e22e](https://github.com/irazex/SIGNA-site/commit/82a265e22e2e83973ce0afacbfdf8acfbb9d5012) 24.11.2026.
