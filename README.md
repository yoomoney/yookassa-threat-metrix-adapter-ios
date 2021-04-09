# ThreatMetrixAdapter

## Описание

`ThreatMetrixAdapter` предоставляет API для вызова публичных методов библиотеки `TMXProfiling`.

`ThreatMetrixAdapter` в runtime определяет, находятся ли зависимости `TMXProfiling.xcframework` и `TMXProfilingConnections.xcframework` в общем Bundle приложения.

## Инструкция по подключению

### Подключить TMXProfiling и TMXProfilingConnections

Для корректной работы адаптера, необходимо подключить зависимости `TMXProfiling.xcframework` и `TMXProfilingConnections.xcframework` в основной Target проекта, в разделе `General` -> `Frameworks, Libraries, and Embedded Content`

В пунтке меню `Embed` выставить `Embed & Sign`
