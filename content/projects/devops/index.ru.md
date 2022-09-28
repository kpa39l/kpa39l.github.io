+++
title = "Дорожная карта по изучению профессии DevOps"
slug = "devopsroadmap"
date = "2022-09-27"
+++

На основе [дорожной карты](https://roadmap.sh/devops) DevOps инженера и SRE создаю расширенный список материалов для изучения.
В итоге, хочу получить учебный курс для сисадминов.

Для удобства представления вот диаграмма в [Mermaid](https://mermaid-js.github.io/mermaid/#/)

{{<mermaid>}}
stateDiagram-v2

 S1: Изучаем язык программирования
         note left of S1
            Python
        end note
         note left of S1
            Ruby
        end note
         note left of S1
            Javascript
        end note
         note right of S1
            Go
        end note
         note right of S1
            Rust
        end note
         note right of S1
            C++
        end note
S1 --> S2
S2: Основы Операционных Систем
    note right of S2
        Управление устройствами ввода/вывода
    end note
    note right of S2
        Виртуализация
    end note
    note right of S2
        Память/Хранилища
    end note
    note right of S2
        Файловые системы
    end note
    note right of S2
        Настройки сети
    end note
    note right of S2
        Сокеты
    end note
    note right of S2
        Процессы
    end note
    note right of S2
        POSIX
    end note
    note right of S2
        systemd
    end note
    note right of S2
        Потоки и параллелеризм
    end note
S2 --> S3
S3: Работа с GNU/Linux
S3 --> S4
S4: Сети, безопаность и протоколы
S4 --> S5
S5: Развертывание сервисов
S5 --> S6
S6: Инфраструктура как код
S6 --> S7
S7: CI/CD инструменты
S7 --> S8
S8: Мониторинг инфраструктуры и ПО
S8 --> S9
S9: Облачные провайдеры
S9 --> S10
S10: Паттерны создания облаков
S10 --> S11
S11: Проложаем учиться           

{{</mermaid>}}