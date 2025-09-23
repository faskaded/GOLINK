# GOLINK
Набор различных ссылок 
## Якори 
1. [Платформы для изучения Go](#id1)
2. [Базовые понятия Go](#id2)
3. [Организация кода](#id3)
4. [Ошибки и их исправления](#id4)
5. [Паттерны программирования в Go](#id5)
6. [Linux](#id6)
7. [Пакеты](#id7)
8. [Серия статей о работе со временем в Go](#id8)
9. [Тестирование](#id9)
10. [Логирование](#id10)
11. [API](#id11)
12. [Конкурентность](#id12)
13. [Горутины](#id13)
14. [Дженерики](#id14)
15. [Redis](#id15)
16. [Алгоритмы](#id16)
17. [Паттерны программирования в Go](#id17)
18. [Введение в основные библиотеки](#id18)
19. [Архитектура](#id19)
20. [БД](#id20)
21. [Практика](#id21)
22. [Go и Docker](#id22)
23. [Сети с Go](#id23)
24. [Внутреннее строение](#id24)
25. [Работа с файлами](#id25)
26. [Go и HashiCorp](#id26)
27. [DevOps](#id27)
28. [Сети](#id28)
29. [Математика](#id29)
30. [Дополнительные инструменты](#id30)
31. [Для кодинга](#id31)
32. [Cheatsheet](#id32)
33. [Интервью](#id33)
34. [Низкоуровневое](#id34)
35. [Обучение SQL](#id35)
36. [ Обьяснений различных понятий](#id36)
37. [Рефакторинг и оптимизация](#id37)



# Платформы для изучения Go <a name="id1"></a>
1. [Exercism](https://exercism.org/tracks) — Куча заданий и базы для отработки навыков.
2. [Vectree](https://vectree.ru/path/38) — Курс от джуна до мидла с мини-проектами и визуальными материалами.
3. https://selectel.ru/blog/courses/ - множество курсов бесплатных от го до иб и различных статей в придачу
4. [CodeBasics](https://code-basics.com) — Бесплатное обучение Go.
5. [Proglib](https://proglib.io/p/samouchitel-po-go-dlya-nachinayushchih-chast-1-osobennosti-i-sfera-primeneniya-go-ustanovka-nastroyka-2023-11-23) — многоступенчатый гайд по гошке
6. [Coddy tech](https://Coddy.tech) — множество курсов по гошке и не только
7. https://www.concurrency.rocks/ - там сразу можно изучить и антипаттерны, конкуренцию, горутины, оптимизации поиска и многое другое, не знал куда именно определеить, поэтому тут
8. [Labex](https://labex.io/ru/courses) — множество практиковаться на виртуальных машинах и практиковать го плюс написать 5 проектов (остальное платное)
9. [Quicref](https://quickref.me) — множество шпор
10. https://codeby.games - отработка навыков хакинга
11. https://www.willem.dev/articles/ - платформа с различнывми понятиями и обьяснениями тем в го
---
# Базовые понятия Go <a name="id2"></a>

1. [Основы Go на YourBasic](https://yourbasic.org/golang/)
2. [Основы го на русском](https://tour.ardanlabs.com/tour/rus/list)
3. [Создание модуля в го](https://go.dev/doc/tutorial/create-module)
4. [Курс по интерфейсам](https://www.calhoun.io/crash-course-on-go-interfaces/ )
5. [Все о build](https://www.kelche.co/blog/go/build/)
6. [Регулярные выражения в Go](https://tproger.ru/articles/puteshestvie-v-golang-regexp)
7. [Итераторы в го](https://bitfieldconsulting.com/golang/iterators)
8. [Указатели в го](https://www.alexedwards.net/blog/a-gentle-introduction-to-pointers)
9. [Конфигурация линтера в го](https://olegk.dev/go-linters-configuration-the-right-version)
10. [Хорошие гайды по гошке](https://www.willem.dev/articles/)
11.  [Go: Structs & Interfaces](https://getstream.io/blog/go-structs-interfaces/)
12.  https://go-cookbook.com - снипеты и примеры кода для го
13.  https://habr.com/ru/companies/lamoda/articles/728920/ - как создать скелет микросервисов
14.  https://habr.com/ru/articles/856272/ Интерфейсы обьяснение, что это и как  

---
# Организация кода <a name="id3"></a>
1. [12 правил организации кода](https://egonelbre.com/thoughts-on-code-organization/)
2. [Еще одна версия 12 правил](https://12factor.net/)
3. [организация кода для модуля](https://go.dev/doc/modules/layout)
4. [структурировании Go-проекта](https://habr.com/ru/company/indriver/blog/690088/)
5. [организация проекта](https://go.dev/doc/modules/layout)
6. [структурировании Go-проекта](https://habr.com/ru/company/indriver/blog/690088/)
7. [Поиск лучшей структуры Go-проекта: история о пути, который прошла команда HUMAN Security}](https://avivcarmi.com/finding-the-best-go-project-structure-part-1/)
8. [Uber гайд написания на гошке](https://github.com/sau00/uber-go-guide-ru/tree/master)
9. [Writing Secure Go Code | Jakub Jarosz](https://jarosz.dev/article/writing-secure-go-code/)
10. https://news.ycombinator.com/item?id=42043939 - Написание безопасного кода на Go
11. 

---
# Ошибки и их исправления <a name="id4"></a>

1. [Го ошибки](https://golang50shad.es/)
2. [Ошибки Go](https://100go.co/)
3. [Leak and Seek: A Go Runtime Mystery или расследование утечки памяти](https://cyolo.io/blog/leak-and-seek-a-go-runtime-mystery)
4. [фундаментальные аспекты обработки ошибок в Go](https://medium.com/@methosi/master-golang-error-handling-a-comprehensive-step-by-step-guide-to-best-practices-698a0530604f)
5. https://www.dolthub.com/blog/2023-04-14-keep-calm-and-panic/ - рассказывает о том, где имеет место паника, почему паника быстрее вызова ошибок и какие компромиссы между ними необходимо учитывать.

---

# Паттерны программирования в Go <a name="id5"></a>

1. [Go Patterns: Перечень паттернов](https://github.com/AlexanderGrom/go-patterns)
2. [Refactoring Guru: Паттерны на Go](https://refactoring.guru/ru/design-patterns/go)
3. [“Common Go Performance Patterns” — распространённые паттерны производительности в Go.](https://goperf.dev/01-common-patterns/)

---
## Linux <a name="id6"></a>

1. https://labs.iximiuz.com/playgrounds - лабы
2. https://kodekloud.com/free-labs
3. https://linuxjourney.com/ - прямо с самого начала для детей
4. https://linux-kernel-labs.github.io/refs/heads/master/index.html - лабы
5. https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html - игра для линукс
6. **[Основы GNU/Linux](https://gnulinux.pro/)**
7. **[Обучение линукс, а именно командам путем детального описания](https://explainshell.com/ )**
---
## Пакеты <a name="id7"></a>

1. **[Список рекомендуемых библиотек](https://threedots.tech/post/list-of-recommended-libraries/)**  
   HTTP, базы данных, разработка CLI, тестирование, observability, конфигурация и многое другое: быстрый обзор 22-х Go-библиотек, проверенных в боевых условиях.
2. **[Валидация данных в Go с Validator](https://thedevelopercafe.com/articles/payload-validation-in-go-with-validator-626594a58cf6)**  
   Базовое руководство по работе с пакетом Validator, который реализует проверку значений для структур и отдельных полей на основе тегов.
3. **[Анонс библиотеки goio](https://habr.com/ru/post/667164/)**  
   Анонс библиотеки потоковой обработки данных goio, вдохновлённой Scala-библиотеками cats-effect и fs2.
4. **[Goyek v2.1.0](https://github.com/goyek/goyek/releases/tag/v2.1.0)**  
   Библиотека для автоматизации задач.

### Серия статей о работе со временем в Go <a name="id8"></a>

- **[Parse timestamp formats](https://dev.to/aohorodnyk/parse-timestamp-on-backend-m0h)**  
- **[Parse time from different non-timestamp formats](https://dev.to/aohorodnyk/parse-time-from-different-non-timestamp-formats-4kb9)**  
- **[Universal time UnmarshalJSON implementation](https://dev.to/aohorodnyk/universal-time-unmarshaljson-implementation-3okm)**  

---

## Тестирование <a name="id9"></a>

### Дополнение к книге "100 ошибок Go" от создателя

- **[Concurrency isn’t always faster in Go](https://teivah.medium.com/concurrency-isnt-always-faster-in-go-de325168907c)**  
   Автор "100 Go Mistakes" делится фундаментальными знаниями о конкурентности в Go и показывает пример, где к производительности конкурентного решения «есть вопросы».

1. **[Установка Go | Изучение Go через тестирование](https://s0xzwasd.gitbook.io/learn-go-with-tests-ru/osnovy-go/install-go)**  
2. **[Тестирование в Go](https://proglib.io/w/40f22786)**
3. https://threedots.tech/post/go-test-parallelism/ - оптимизация и визуализация параллелизма тестов Go 
4. **[GolangCI-Lint](https://golangci-lint.run/)**
5. https://habr.com/ru/companies/netologyru/articles/947796/ - интеграционное тестирование 
   Библиотека для тестов.
6. **[GopherCon 2022](https://www.youtube.com/watch?v=v24wrd3RwGo&list=PL2ntRZ1ySWBfiSJSt-zPRbVSMDfK0EwQC)**  
   От синтаксического анализа и сборки мусора до WebAssembly и фаззинг-тестирования: доклады на GopherCon 2022.
7. **[Comprehensive Guide to Testing in Go](https://blog.jetbrains.com/go/2022/11/22/comprehensive-guide-to-testing-in-go/)**  
   Полное руководство по тестированию.
8. **[Про фаззинг](https://habr.com/ru/company/kaspersky/blog/696724/)**  
9. **[How to Write Accurate Benchmarks in Go](https://teivah.medium.com/how-to-write-accurate-benchmarks-in-go-4266d7dd1a95)**  
   Разбор четырёх распространённых ловушек, которые ведут к неточностям тестирования в Go.
10. **[Create Your Tests Easily](https://habr.com/ru/company/ozontech/blog/672678/)**  
   Анонс open source библиотеки от Ozon Tech в BDD-стиле, которая облегчает создание автотестов.
11. **[Безопасность цепочки поставок с Go](https://t.me/goproglib/3560)**  

### Безопасность цепочки поставок: серия статей Go-разработчика

- **[Часть 1](https://security.googleblog.com/2023/04/supply-chain-security-for-go-part-1.html)**  
- **[Часть 2](https://security.googleblog.com/2023/06/supply-chain-security-for-go-part-2.html)**  
- **[Часть 3](https://security.googleblog.com/2023/07/supply-chain-security-for-go-part-3.html)**  

### Серия руководств о фаззинг-тестировании в Go

11. **[Random testing in Go](https://bitfieldconsulting.com/golang/random-testing)**  
12. **[Fuzz tests in Go](https://bitfieldconsulting.com/golang/fuzz-tests)**  
13. **[Writing a Go fuzz target](https://bitfieldconsulting.com/golang/fuzz-target)**  
14. **[Finding bugs with fuzzing](https://bitfieldconsulting.com/golang/bugs-fuzzing)**  

---

## Логирование <a name="id10"></a>

1. **[Полный гайд по Zerolog](https://betterstack.com/community/guides/logging/zerolog/)**  
   Как установить, настроить и использовать Zerolog logger в Go-приложении.
2. **[Логирование в Go: от основ до профи](https://www.bytesizego.com/blog/guide-to-logging-in-go)**  
3. **[Обработка огромных лог-файлов](https://www.madhur.co.in/blog/2023/06/10/processing-huge-log-files.html)**  
   Обработка огромных лог-файлов с помощью Go и Python.

---

## API <a name="id11"></a>

1. **[Golang APIs: скелетон для будущих проектов](https://blog.devgenius.io/golang-apis-a-skeleton-for-your-future-projects-a082dc4d6818)**  
   Серия статей о построении скелетона для API на Go.
2. https://escape.tech/academy/ - можно изучить защиту апи и ее атаку, для тестирования своего продукта
3. https://rapidapi.com/hub - 51 тысяча различных апи

---

## Конкурентность <a name="id12"></a>

1. **[Concurrency, race conditions и контроль](https://sayedalesawy.hashnode.dev/concurrency-race-conditions-and-concurrency-control)**  
   Что такое конкурентность (можно читать перед книгой о конкурентности).
2. **[Шаблоны конкурентности](https://dev.to/karanpratapsingh/advanced-concurrency-patterns-in-go-2je1)**  

---

## Горутины <a name="id13"></a>

- **[Внутренности горутин и каналов в Go](https://proglib.io/w/94177b59)**
- **[Goroutines in Go: A Practical Guide to Concurrency](https://getstream.io/blog/goroutines-go-concurrency-guide/)**

---

## Дженерики <a name="id14"></a>

1. **[Туториал по дженерикам в Go](https://kovardin.ru/articles/go/generics/#%D0%BF%D0%BE%D1%87%D0%B5%D0%BC%D1%83-%D1%82%D0%B0%D0%BA-%D0%B4%D0%BE%D0%BB%D0%B3%D0%BE-%D0%B6%D0%B4%D0%B0%D0%BB%D0%B8)**  
   Введение в дженерики.
2. **[Когда использовать дженерики](https://go.dev/blog/when-generics)**  
3. **[Go by Example](https://gobyexample.com/)**  
   Информация о дженериках.

---

## Redis <a name="id15"></a>

- **[Глубокое погружение в Redis](https://architecturenotes.co/redis/)**  
   От топологий Redis до data persistence и разветвления процессов.
- **[Redis и Go](https://t.me/goproglib/3890)**  
- **[Кэширование в Go с Redis](https://voskan.host/2023/08/14/golang-redis-caching/)**  
   Подробное руководство по повышению производительности.

---

## Алгоритмы <a name="id16"></a>

1. **[TheAlgorithms/Go](https://github.com/TheAlgorithms/Go)**  
2. **[Реализация дерева отрезков на Go](https://rtoch.com/posts/golang-segment-tree/)**  
   Подробная реализация Segment Tree.
3. **[R*-tree в Go](https://habr.com/ru/post/666904/)**  
   Теория и детали реализации подвида алгоритма R-tree.
4. **[Алгоритмы для ML и девопс](https://yandex.ru/yaintern/training)**
5. **[бесплатный курс по алгоритмам от Слерм](https://slurm.io/algorithms)**
6. https://github.com/tayllan/awesome-algorithms - все о алгаритмах
7. https://eecs376.github.io/notes/algorithms.html - учебник по алгоритмам, а также CS
8. https://habr.com/ru/articles/794556/ - шпаргалка по алгоритмам
9.  **[Учебник по алгоритмам](https://nikku1234.github.io/Certification/Data%20Structures%20and%20Algorithms/Learning%20Algorithms%20Through%20Programming%20and%20Puzzle%20Solving%20(%20PDFDrive.com%20).pdf)**
10. https://www.bigocheatsheet.com/pdf/big-o-cheatsheet.pdf - шпаргалка по сложностям алгоритмов
  
   

---

## Паттерны программирования в Go <a name="id17"></a>

4. **[Go-patterns](https://github.com/AlexanderGrom/go-patterns)**  
   Перечисление всех паттернов для Go.
5. **[Рефакторинг и паттерны на Go](https://refactoring.guru/ru/design-patterns/go)**  
   (Требуется VPN).

---

## Введение в основные библиотеки <a name="id18"></a>

1. **[Cover - Spaceship Go](https://blasrodri.github.io/spaceship-go-gh-pages/cover.html)**  
2. **[Requests v0.23.4](https://github.com/carlmjohnson/requests/releases/tag/v0.23.4)**  
3. **[Zap для Go-разработчика](https://betterstack.com/community/guides/logging/go/zap/)**  
   Подробное введение в популярный пакет логирования.

---

## Архитектуры <a name="id19"></a>

4. **[Go-coffeeshop](https://github.com/thangchung/go-coffeeshop)**  
   Пример приложения для кофейни на Go. Архитектура.
5. **[Domain Driven Design в Go](https://habr.com/ru/companies/oleg-bunin/articles/791420/)**
6. **[Architecture Notes Archive](https://architecturenotes.co/archive)**  
   Полезные статьи.
7. https://laurentsv.com/blog/2024/10/19/no-nonsense-go-package-layout.html - структура проекта

---

## БД <a name="id20"></a>

1. **[Организация доступа к базе данных](https://www.alexedwards.net/blog/organising-database-access)**  
   Разбор четырёх методов организации доступа к базе данных на Go.
2. **[Миграции базы данных с Migrate](https://thedevelopercafe.com/articles/database-migrations-in-go-using-migrate-package-5735cf056231)**  
   Базовое руководство по использованию пакета migrate.
3. **[Отслеживание изменений схемы базы данных](https://betterprogramming.pub/database-migrations-f3a227e29f5f)**  
   Советы и простые практические приёмы.
4.**[Книга по PostgreSQL]([https://betterprogramming.pub/database-migrations-f3a227e29f5f](https://u.habr.com/lXpYA)** 

---

## Практика <a name="id21"></a>

7. **[Coding Challenges](https://codingchallenges.fyi/challenges/intro)** 
   Челленджи.
8. **[Interactive Go Challenges](https://tutorialedge.net/challenges/go/)**  
   Челленджи по Go.
10. **[Go Telegram Bot API](https://go-telegram-bot-api.dev/)**  
   Полное руководство по созданию бота на Go.
11. **[Gophercises](https://gophercises.com/)** 20 практических задач.
12. https://youtu.be/bymQakvTY40?si=hXvBPayxuDd_sK96 -  Разработка полноценного распределенного хранилища файлов на Go
13. **[GraphQL-сервер на Go](https://tech.trivago.com/post/2023-05-17-building-our-first-graphql-server-with-go-an-implementation-guide)**  
    Реализация GraphQL-сервера.
14. **[CLI-инструмент с Cobra](https://www.twilio.com/blog/use-cobra-build-go-powered-clis)**  
    Пошаговый гайд по созданию CLI-инструмента.
15. **[Бессерверный бот Discord](https://www.openfaas.com/blog/build-a-serverless-discord-bot/)**  
    Разработка с OpenFaaS и Go.
16. **[FaaS в Go с WASM](https://eli.thegreenplace.net/2023/faas-in-go-with-wasm-wasi-and-rust/)**  
    Пишем простой FaaS-сервер для модулей на WASM.
17. **[Отладка CLI-проектов](https://youtu.be/vInn3KNF1x4)**  
    Отладка CLI-проектов на Go с помощью VS Code.
18. **Пишем Uber на Go**  
    - [Часть 1](https://medium.com/@mhrlife/building-an-online-taxi-app-like-uber-with-golang-part-1-nearby-taxis-c509168ef59f)  
    - [Часть 2](https://medium.com/@mhrlife/building-an-online-taxi-app-like-uber-with-golang-part-2-scalability-and-authorization-4583d51f22a3)  
    - [Часть 3](https://medium.com/@mhrlife/building-an-online-taxi-app-like-uber-with-golang-part-3-redis-to-rescue-ab579cfdd299)  
    - [Часть 4](https://medium.com/@mhrlife/building-an-online-taxi-app-like-uber-with-golang-part-4-why-golang-1cd70d416417)  
19. **[Реализация анонимной сети](https://habr.com/ru/articles/745256/)**
20. **[Создание VM](https://blog.phakorn.com/posts/2025/building-a-simple-vm/)** - 
21. **[Создание мониторинга](https://encore.dev/docs/tutorials/uptime)**  
22. **[Разработка и публикация Go-пакета](https://medium.com/the-godev-corner/how-to-create-publish-a-go-public-package-9034e6bfe4a9)**  
    Пошаговое руководство.
23. **[Видео](https://youtu.be/gnchfOojMk4)**
24. https://totallygamerjet.hashnode.dev/writing-an-os-in-go-the-bootloader - создание ОС
25. **[Practical Go Lessons](https://www.practical-go-lessons.com/)**  
    Книга для понимания устройства Go.
26. **[One Billion Row Challenge](https://r2p.dev/b/2024-03-18-1brc-go/)**  
    Решение задачи 1BRC.
27. **[Terminal User Interface с Go](https://earthly.dev/blog/tui-app-with-go/)**  
28. **[Балансировщик нагрузки](https://domenicoluciani.com/2024/02/12/creating-an-application-layer-load-balancer.html)**  
    Создание балансировщика нагрузки прикладного уровня.
29. **[DNS-преобразователь](https://domenicoluciani.com/2024/05/07/create-dns-resolver.html)**  
    Создание DNS-преобразователя с помощью Golang.
30. **[DevOps Exercises](https://github.com/bregman-arie/devops-exercises?tab=readme-ov-file)**  
    Задания для практики по Go.
31. **[Анонимный мессенджер](https://habr.com/ru/post/701488/)**  
    Теория и практика разработки на основе HLS.
32. **[100 Golang Exercises](https://github.com/cblte/100-golang-exercises)**  
    Челленджи.
33. **[WebSocket эхо-сервер](https://habr.com/ru/post/674694/)**  
    Имплементация простого WebSocket эхо-сервера.
34. **[Распределённая трассировка](https://dev.to/signoz/implementing-distributed-tracing-in-a-golang-application-5cm1)**  
    Руководство с OpenTelemetry и SigNoz.
35. **[Внешняя Go-библиотека](https://habr.com/ru/company/ozontech/blog/668254/)**  
    Написание удобной для экспорта и импорта библиотеки.
36. **Машинное обучение на Go**  
    - [Теория](https://medium.com/@kcatstack/sentiment-analysis-naive-bayes-classifier-from-scratch-part-1-theory-4949115ba13)  
    - [Практика](https://medium.com/@kcatstack/naive-bayes-classifier-from-scratch-part-2-nlp-in-golang-81c2a103ee06)  
37. **[Компилятор, часть 1](https://eli.thegreenplace.net/2019/go-compiler-internals-adding-a-new-statement-to-go-part-1/)**  
38. **[Компилятор, часть 2](https://eli.thegreenplace.net/2019/go-compiler-internals-adding-a-new-statement-to-go-part-2/)**  
39. **[Распределённое key-value хранилище](https://notes.eatonphil.com/2023-05-25-raft.html)**  
40. **[Анализ Go-бинарей с gftrace](https://0xdf.gitlab.io/2024/05/07/gftrace.html)**  
41. **[Реверс Go-бинарей с Ghidra](https://youtu.be/J2svN8h21oo)**  
42. **[Самый маленький Go-бинарный файл](https://totallygamerjet.hashnode.dev/the-smallest-go-binary-5kb)**  
    Создание компилятора C на Go.
43. **[Terminal User Interface с Go](https://earthly.dev/blog/tui-app-with-go/)**  
44. **[Приложения с GUI](https://proglib.io/w/b1a5c90d)**  
45. **[Hello World в ядре Linux](https://blog.sigma-star.at/post/2023/07/embedded-go-prog/)**  
46. **Создание шаблона аутентификации с нуля (Go, GoFiber, PostgreSQL)**  
    - [Сервер с PostgreSQL](https://dev.to/mdfaizan7/create-a-server-with-postgresql-in-go-part-1-3-of-go-authentication-series-3127)  
47. **[Кэширование Go-тестов в CI](https://www.airplane.dev/blog/caching-golang-tests-in-ci)**  
    Как сократить время прогона тестов в CI.

### Go и Docker <a name="id22"></a>

- **[Отладка в Docker](https://www.kenaqshal.com/blog/debugging-dockerized-go-applications)**  Отладка Go-приложений в Docker-контейнерах с VS Code.
- https://dev.to/shaggyrec/run-a-golang-nginx-and-react-app-in-docker-59kn - Гайд для новичков по запуску приложения на Go + React в Docker
- **[Репликация и балансировка](https://betterprogramming.pub/replicating-and-load-balancing-go-applications-in-docker-containers-with-consul-and-fabio-3ec5eed15154)**  
   Репликация и балансировка нагрузки с Consul и Fabio.
  

---

## Сети с Go <a name="id23"></a>

1. **[Типобезопасные HTTP-запросы](https://dev.to/kevwan/sending-type-safe-http-requests-with-go-5h2l)**  
   Заметки по использованию пакета httpc из go-zero.
2. **[Сетевое программирование](https://itnext.io/network-programming-in-go-389cd89ab874)**  
   Пишем простой TCP-сервер с логированием.
3. **[Mastering Go's net/http Package](https://dev.to/ombima/mastering-gos-nethttp-package-a-comprehensive-guide-for-beginners-3bc2)**  
   Полное руководство для новичков.

---

## Внутреннее строение <a name="id24"></a>

1. **[Go CPU Profiler под капотом](https://sumercip.com/posts/inside-the-go-cpu-profiler/)**  
2. **[Системные вызовы Go в Windows](https://leandrofroes.github.io/posts/An-in-depth-look-at-Golang-Windows-calls/)**  
3. **[Атомики в Go](https://habr.com/ru/articles/744822/)**  
   Обзор особенностей реализации и отличий от мьютексов.
4. **[Знакомство с кэшем ЦП](https://www.ardanlabs.com/blog/2023/07/getting-friendly-with-cpu-caches.html)**  
5. **[Руководство по сборщику мусора Go](https://go.dev/doc/gc-guide)**  
6. **[Как устроен тип Map](https://youtu.be/P_SXTUiA-9Y)**  
7. **[Память в Go](https://habr.com/ru/companies/vk/articles/776766/)**  
   От теории к практике.
8. **[Замыкания в Go](https://proglib.io/w/7a66a3fb)**  
9. **[Планировщик Go](https://www.youtube.com/watch?v=P2Tzdg8n9hw&t=0s)**  
   Видеогайд от Владимира Балуна.
10. **[RPC и gRPC](https://youtu.be/gnchfOojMk4)**  
    Наглядное объяснение механизмов работы.
11. **[Презентация о работе Go](https://talks.golang.org/2012/splash.slide)**  
12. **[Concurrency is not Parallelism](https://blog.golang.org/concurrency-is-not-parallelism)**  
    Сложно, но полезно для понимания языка.
13. **[gRPC-Gateway](https://habr.com/ru/companies/ozonbank/articles/817381/)**  
    Детальный взгляд на стандартизацию.
15. **[Компиляция в машинный код](https://getstream.io/blog/how-a-go-program-compiles-down-to-machine-code/)**
16. https://youtu.be/7K0HweCBJwI - внутренее строение аллокатора
17. https://www.youtube.com/watch?v=10LW7NROfOQ&t=14s устройство slice
18. https://www.youtube.com/watch?v=P_SXTUiA-9Y&t=19s - устройство map
19. https://www.youtube.com/watch?v=ZTJcaP4G4JM&t=134s - устройство каналов
20. https://antonz.org/go-1-21-builtins/ - устройство - min max clear
21.  **[как Go управляет памятью](https://nghiant3223.github.io/2025/06/03/memory_allocation_in_go.html)**
22. **[Go Internals](https://cmc.gitbook.io/go-internals)**  
    Внутреннее устройство Go.
    
    

### Серия о слайсах под капотом 

- **[Build your own slice: Arrays and slices](https://www.willem.dev/articles/build-your-own-slice-start-here/)**  
- **[Build your own slice: Append and Copy](https://www.willem.dev/articles/build-your-own-slice-append-copy/)**  

---

## Работа с файлами <a name="id25"></a>

1. **[Работа с JSON](https://developer20.com/json/)**  
   Практическое руководство.
2. **[Обработка статических файлов](https://thedevelopercafe.com/articles/serving-static-files-in-go-f4acf2b4cfe5)**  
   Использование http.Dir и http.FileServer.

---

## Go и HashiCorp <a name="id26"></a>

1. **[Управление секретами с Vault](https://www.twilio.com/blog/manage-go-application-secrets-using-vault)**  
2. **[HashiCorp Vault для хранения секретов](https://habr.com/ru/articles/653927/)**  
   Гайд на основе Go-проекта.

---

## DevOps <a name="id27"></a>

- **[Самоучитель по CI/CD и Kubernetes](https://ru.werf.io/guides/golang/100_basic.html)**  
   Бесплатный курс для Go-разработчиков.
- **[Приватные модули Go с Docker](https://medium.com/the-godev-corner/how-to-create-a-go-private-module-with-docker-b705e4d195c4)**  
   Пошаговый гайд.
- **[Учебник по Git](https://coderlessons.com/tutorials/devops/uchitsia-git/git-tutorial)**  
   Множество гайдов с инструментами.
- **[CNCF Landscape](https://landscape.cncf.io/)**  
   Все технологии.
- **[DevSecOps обучение](https://devsecopsguides.com/docs/rules/go/)**
- **[внедрение CI CD](https://proglib.io/sh/k31RpYdjES)** 

### Kubernetes 

- **[Cilium и AKS](https://isovalent.com/blog/post/cilium-egress-gateway-aks/)**  
   Развёртывание Cilium и выходного шлюза в Azure Kubernetes.
- **[Kube Academy](https://kube.academy/courses)**  
   Курс по Kubernetes.
- **[Kubernetes VMware Cloud](https://vmc.techzone.vmware.com/kubernetes-vmware-cloud-course)**  
   Курс по Kubernetes.
- https://docs.dobry-kot.ru/blog/kubernetes-the-hard-way/ - полный пошаговый гайд по сборке Kuberentes

### Сети <a name="id28"></a>

- **[Сети с нуля с картинками](https://www.networksfromscratch.com/1.html)**
- **[Сетевое устройство и обьяснение работы интернета с картинками](https://internetingishard.netlify.app/)**
- **[8 частей о сетях](https://habr.com/ru/articles/307252/)**  
- **[Сегментация сетей](https://habr.com/ru/articles/588705/)**  
   Для самых маленьких.
- **[Практика сетей](https://linkmeup.gitbook.io/sdsm)**  
- **[Реверс-прокси с динамическим бэкендом](https://www.artur-rodrigues.com/tech/2023/03/12/reverse-proxy-with-dynamic-backend-selection.html)**
- **[Вкратце об анонимных сетях и задачах анонимизации | Proxy, Onion, Dining Cryptographers](https://habr.com/ru/articles/912554/)**
- **[Коллекция материалов по сетям ](https://github.com/SE-adm/Awesome-network/tree/main)**
- **[Основные компоненты сетей](http://infocisco.ru/network_components.html)**

### Математика <a name="id29"></a>

- **[Начальная математика](https://www.youtube.com/watch?v=NyAggwR2trA&list=PLtYNtkKY2LiZsKeA_Csrlh1yZoQDojhVq&ab_channel=Myuniversity)**  
- **[Мат анализ](https://www.youtube.com/@teachin-ru/search?query=%D0%B1%D1%83%D1%82%D1%83%D0%B7%D0%BE%D0%B2)**
- **[Мат логика](https://www.youtube.com/watch?v=GvYjRFNbms8&list=PL4_hYwCyhAvap4WZdKoNvmJYxDZgGmkhc&ab_channel=%D0%9B%D0%B5%D0%BA%D1%82%D0%BE%D1%80%D0%B8%D0%B9%D0%A4%D0%9F%D0%9C%D0%98)**
- **[Теория Галуа](https://www.youtube.com/watch?v=h-EOann0fVk&list=PLeURvsEJKXbj_Y2QWIoB2JCwo_HpZegz_&ab_channel=Myuniversity)**


## Дополнительные инструменты <a name="id30"></a>

- **[Hotkey Cheatsheet](https://hotkeycheatsheet.com/ru)**  
   Все шорткаты для разных программ.
- **[Airtable](https://airtable.com/)**  
   Фриланс.


### Для кодинга <a name="id31"></a>

1. **[VS Code для Go](https://bitfieldconsulting.com/golang/vs-code-go)**  
   Обзор полезных возможностей.
2. **[Настройка Neovim для Go](https://habr.com/ru/post/678298/)**  
   Использование плагинов Lua.

### Cheatsheet <a name="id32"></a>

4. **[Go Cheatsheet](https://devhints.io/go)**
5. **[Cheatsheet для всех языков](https://quickref.me/)**

---

## Интервью, собесы, задания<a name="id33"></a>
- https://yeahub.ru/questions?page=1&status=all&specialization=23 - вопросы по го для собеседования и не только
- **[Подготовка к алгоритмическим интервью](https://habr.com/ru/companies/cloud_mts/articles/735348/)**  
   Опыт с примерами на Go.
- **[Задачи и вопросы по програмиированию с реальных собеседований](https://it-interview.io/interview-tasks)**
- **[Тестовые задания](https://github.com/Hexlet/ru-test-assignments?tab=readme-ov-file)**
- **[Тестовые задания и вопрос 2](https://it-interview.io/interview-tasks)**
- **[Чеклист для проверки себя перед собесом](https://gist.github.com/Voley/fbbb7b0d822464ac03999ee85a3d2c4f)**
- **[Техническое собеседование на Senior Go Developer на вб](https://youtu.be/N12lmpYUXFo)**
- **[Техническое собеседование на Senior Go Developer на вб 2](https://youtu.be/TU9ap77Qupw)**
- **[Техническое собеседование на Senior Go Developer в IDS](https://youtu.be/H4HLv3wESlE)**
- **[Техническое собеседование на Senior Go Developer в Холодильник ру](https://youtu.be/dbUFVRKGU3A)**
- **[Техническое собеседование на Senior Go Developer в Indrive Кипр](https://youtu.be/LyIzIqDaXgE)**
- **[Техническое собеседование на Senior Go Developer в Займиго (Кредиска)](https://youtu.be/FS6IZHE4acs)**
- **[Техническое собеседование на Senior Go Developer в Ozon](https://youtu.be/Q6FZ4q-_YKQ)**
- **[Техническое собеседование на Senior Go Developer в Самокат](https://youtu.be/EuXUvcYtGdI)**
- **[Техническое собеседование на Senior Go Developer в EMCD](https://youtu.be/UIKMsnmhw0A)**
- **[Техническое собеседование на Senior Go Developer в GsmSoft](https://youtu.be/Bq07XvvS6_E)**
- **[Техническое собеседование на Senior Go Developer в Startribe](https://youtu.be/VhFqMGMwot8)**
- **[Техническое собеседование на Senior Go Developer в Evrone](https://youtu.be/exEJvhGfd74)**
- **[Собеседование на Senior Go Developer в Wildberries Склад](https://youtu.be/tDNMk0fvhe4)**
- **[Собеседование на Middle Go Developer в ZTC (Zonatelecom)](https://youtu.be/_BbcSh0bCZQ)**
- Решение задач из предыдущей записи https://www.bolshoyvopros.ru/questions/3388582-kak-najti-falshivuju-monetu-odnim-vzveshivaniem.html
- **[Собеседование на Senior Go Developer на 400к в Автомакон](https://youtu.be/N_TLjhNJgs0)**
- **[Собеседование на Go Developer в Сбермаркет](https://youtu.be/0vL6NhM8h0E)**
- **[Самое токсичное собеседование из опыта - Middle Go Developer (400к)](https://youtu.be/ICiGUsleGsU)**
- **[Собеседование на Senior Go Developer (400к) МТС Cloud](https://youtu.be/bGa2hBnac1w)**
- **[Собеседование на Senior Go Developer (400к) Бери Заряд](https://youtu.be/p6kix_4EClg)**
- **[Собеседование на Senior Go Developer (450к) Positive Technologies](https://youtu.be/Ko_2nMrsgVU)**
- **[Собеседование на Middle Go Developer (400к) Astral Soft](https://youtu.be/kjVDYXVM3oo)**
- **[Собеседование на Middle Go Developer (400к) Notix Games](https://youtu.be/vEZk1FLY83A)**
- **[Собеседование на Middle Go Developer (400к) Notix Games 2 часть ](https://youtu.be/IBzfUvTPkss)**
- **[Собеседование на Middle Go Developer (400к) Авито](https://youtu.be/fj3Fv-SaO14)**
- **[Систем дизайн собеседование на 400к CyberOk](https://youtu.be/-Nj612lClvA)**
  Задачи для live coding
- 1. https://drive.google.com/drive/folders/155UD4MGbqf2Vm1b1Tu_80AtQiHdINNkM  

- 2. https://github.com/nosuchpersonn/golang_interview/tree/main/%D0%97%D0%B0%D0%B4%D0%B0%D1%87%D0%B8  

- 3. https://docs.google.com/document/d/1OhigKR_M4EM5rL1B7jpoYqxYEwyzQzoTW4MtL27Ua00/edit#heading=h.tvecg1f7bylq  

- 4. https://docs.google.com/document/d/1OXf2Ju-jz1DtkcczW6AfAAVR4ZueZlztRy6RlsUik_Y/edit#heading=h.jwfk49js0v6
---

## Низкоуровневое <a name="id34"></a>

- **[Манипуляции с битами в Go](https://habr.com/ru/companies/ruvds/articles/744230/)**  

---
## Обучение SQL <a name="id35"></a>

- **[Манипуляции с битами в Go](https://habr.com/ru/companies/ruvds/articles/744230/)**  

---
## Обьяснений различных понятий (не только про го) <a name="id36"></a>

- **[Можно узнать о разных вещах в программировании](https://se-education.org/learningresources/)**  


---

## Рефакторинг и оптимизация<a name="id37"></a>

- **[Рефакторинг изучение темы](https://roadmap.sh/best-practices/code-review)**
- https://golang.withcodeexample.com/blog/advanced-techniques-for-code-optimization-in-go/ - оптимизация кода на го
- https://dev.to/yanev/optimizing-memory-usage-in-go-mastering-data-structure-alignment-4beb - оптимизация использования памяти в Go: освоение выравнивания структуры данных!
- https://nuancesprog.ru/p/18145/ - Рефакторинг кода Go для тестопригодности: возможности интерфейсов
- https://habr.com/ru/companies/yadro/articles/842314/ - Три способа оптимизировать работу с памятью на Go с помощью memory pools


---
