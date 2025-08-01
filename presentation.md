---
## Front matter
lang: ru-RU
title: Презентация к внешнему курсу
subtitle: Презентация
author:
  - Филипьева К.Д.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 17 мая 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
 
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Филипьева Ксения Дмитриевна
  * Студент
  * Российский университет дружбы народов
  * [1132230795@pfur.ru](mailto:1132230795@pfur.ru)

:::
::: {.column width="30%"}

:::
::::::::::::::

## Цель работы

Целью работы является выполнение контрольных заданий первого модуля курса "Основы кибербезопасности" по теме "Безопасность в сети".

## Устройство интернета и сетевые протоколы

HTTPS — это протокол прикладного уровня, который требуется в первом вопросе.

![Вопрос 2.1](image/1.png){width=70%}

## 

TCP дал название модели.

![Вопрос 2.1](image/2.png){width=70%}

## 

IP-адрес должен состоять из 4 или 6 чисел в диапазоне от 0 до 255.

![Вопрос 2.1](image/3.png){width=70%}

## 

DNS-сервер связывает доменное имя с IP-адресом.

![Вопрос 2.1](image/4.png){width=70%}

## 

Протоколы по уровням TCP/IP.

![Вопрос 2.1](image/5.png){width=70%}

## 

HTTP не шифрует данные, в отличие от HTTPS.

![Вопрос 2.1](image/6.png){width=70%}

## 

TLS настраивается клиентом и сервером.

![Вопрос 2.1](image/7.png){width=70%}

## 

Установление соединения по TLS требует согласования.

![Вопрос 2.1](image/8.png){width=70%}

## 

Фаза TLS-рукопожатия включает выбор алгоритма, проверку, создание ключа.

![Вопрос 2.1](image/9.png){width=70%}

## Идентификация через куки

Куки-файлы содержат параметры сессии.

![Вопрос 2.2](image/10.png){width=70%}

## 

Куки не обеспечивают безопасную передачу данных.

![Вопрос 2.2](image/11.png){width=70%}

## 

Сервер формирует куки и передаёт их клиенту.

![Вопрос 2.2](image/12.png){width=70%}

## 

Сессионные куки удаляются при закрытии браузера.

![Вопрос 2.2](image/13.png){width=70%}

## Анонимность в сети через TOR

Маршрутизация в Tor включает три узла: охранный, промежуточный, выходной.

![Вопрос 2.3](image/14.png){width=70%}

## 

IP скрыт от охранного и промежуточного узлов.

![Вопрос 2.3](image/15.png){width=70%}

## 

Tor использует три узла для формирования общего ключа шифрования.

![Вопрос 2.3](image/16.png){width=70%}

## 

Tor используется для маскировки личности.

![Вопрос 2.3](image/17.png){width=70%}

## Wi-Fi и его защита

Wi-Fi — это технология по стандарту IEEE 802.11.

![Вопрос 2.4](image/18.png){width=70%}

## 

Он функционирует на канальном уровне.

![Вопрос 2.4](image/19.png){width=70%}

## 

WEP устарел и уязвим.

![Вопрос 2.4](image/20.png){width=70%}

## 

Шифрование Wi-Fi защищает соединение.

![Вопрос 2.4](image/21.png){width=70%}

## 

WPA2 Personal — для дома, Enterprise — для компаний.

![Вопрос 2.4](image/22.png){width=70%}

## Шифрование диска

Рекомендуется защищать основной раздел и загрузочную область.

![Вопрос 3.1](image/23.png){width=70%}

## 

Используется симметричное шифрование.

![Вопрос 3.1](image/24.png){width=70%}

## 

Есть встроенные средства и альтернативы с открытым кодом.

![Вопрос 3.1](image/25.png){width=70%}

## Безопасные пароли

Надёжный пароль содержит буквы, цифры, символы.

![Вопрос 3.2](image/26.png){width=70%}

## 

Пароли хранятся в менеджерах, не в мессенджерах.

![Вопрос 3.2](image/27.png){width=70%}

## 

CAPTCHA отличает человека от робота.

![Вопрос 3.2](image/28.png){width=70%}

## 

Пароли хранятся в виде хэшей.

![Вопрос 3.2](image/29.png){width=70%}

## 

Соль усиливает защиту пароля.

![Вопрос 3.2](image/30.png){width=70%}

## 

Рекомендуется использовать длинные и сложные пароли.

![Вопрос 3.2](image/31.png){width=70%}

## Фишинг

Фишинговые сайты маскируются под настоящие.

![Вопрос 3.3](image/32.png){width=70%}

## 

Фишинг может прийти с адреса знакомого.

![Вопрос 3.3](image/33.png){width=70%}

## Вредоносные программы

Спуфинг — подделка адреса отправителя.

![Вопрос 3.4](image/34.png){width=70%}

## 

Трояны маскируются под обычное ПО.

![Вопрос 3.4](image/35.png){width=70%}

## Шифрование в мессенджерах

При первом сообщении создаётся ключ.

![Вопрос 3.5](image/36.png){width=70%}

## 

Сквозное шифрование скрывает переписку от сервера.

![Вопрос 3.5](image/37.png){width=70%}

## Основы криптографии

Асимметричное шифрование: публичный и приватный ключи.

![Вопрос 4.1](image/38.png){width=70%}

## 

Хэш-функции преобразуют данные в строку фиксированной длины.

![Вопрос 4.1](image/39.png){width=70%}

##Алгоритмы цифровых подписей.

![Вопрос 4.1](image/40.png){width=70%}

## 

MAC использует общий ключ.

![Вопрос 4.1](image/41.png){width=70%}

## 

Диффи-Хеллман — для обмена ключами.

![Вопрос 4.1](image/42.png){width=70%}

## Электронная подпись

ЭЦП использует криптографию с открытым ключом.

![Вопрос 4.2](image/43.png){width=70%}

## 

Верификация включает обновление, подпись, открытый ключ.

![Вопрос 4.2](image/44.png){width=70%}

## 

Подпись обеспечивает целостность, личность и неотказуемость.

![Вопрос 4.2](image/45.png){width=70%}

## 

УКЭП приравнивается к обычной подписи.

![Вопрос 4.2](image/46.png){width=70%}

## 

Сертификат заверяется подписью УЦ.

![Вопрос 4.2](image/47.png){width=70%}

## Платёжные системы

Популярные системы: Visa, MasterCard, МИР.

![Вопрос 4.3](image/48.png){width=70%}

## 

Факторы идентификации: знание, устройство, биометрия, местоположение.

![Вопрос 4.3](image/49.png){width=70%}

## 

Онлайн-платежи используют MFA.

![Вопрос 4.3](image/50.png){width=70%}

## Блокчейн

Proof-of-Work — валидация через вычисления.

![Вопрос 4.4](image/51.png){width=70%}

## 

Свойства блокчейна: неизменяемость, согласованность, доступность, открытость.

![Вопрос 4.4](image/52.png){width=70%}

## 

Участники подписывают транзакции закрытым ключом.

![Вопрос 4.4](image/53.png){width=70%}

## Общий результат

Финальный результат

![Финал](image/final.png){width=70%}

