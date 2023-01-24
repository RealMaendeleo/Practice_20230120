# ChangeLog
## [2.1.0] 2021-06-09
### Added
- Добавлена новая версия Dummy инвокера отдельным классе. Поведение задается через параметры шага или строку настроек.
Добавлены новые настройки поведения:
    - sleepTime - время остановки потока
    - emptyResponse - флаг пустого ответа
## [2.1.1] 2021-08-02
### Added
- Добавлена возможность передавать контекст вызова инвокера (из него будет браться количество попыток запроса на сервер), а также сборка контекста вызова инвокера в случае ожидания.
- Добавлена новая настройка поведения:
 - retryCount - количество запросов на сервер (после его истечения инвокер вернёт успешный ответ)
## [2.2.0] 2021-10-29
### Added
- Добавлен инвокер для тестирования post запроса(только url)
## [2.3.0] 2021-10-29
### Added
- DummyInvokerV2 Добавлен параметр sourceerror для воспроизведения получения ошибки от источника
## [2.3.1] 2022-12-01
### Added
- LoadTestInvoker Добавлена возможность получения параметров через call