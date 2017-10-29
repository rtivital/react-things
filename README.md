# React Things
Коллекция материалов для изучения ES2015, React, Redux, Webpack, Babel и всего остального.

Думаешь, что подборка не полная? Присылай Pull Request с недостающими материалами!

---

Содержание:
1. [ES2015: то, что действительно нужно](#es2015-то-что-действительно-нужно)
2. [React: Основы основ](#react-Основы-основ)
3. [Ныряем в React с головой](#Ныряем-в-react-с-головой)
4. [Робкое знакомство с Redux](#Робкое-знакомство-с-redux)
5. [Продвинутый Redux](#Продвинутый-redux)
6. [Роутинг](#Роутинг)
7. [Архитектура приложения](#Архитектура-приложения)
8. [От и до: уроки по созданию полноценных приложений](#От-и-до-уроки-по-созданию-полноценных-приложений)
9. [Тестирование](#Тестирование)
10. [Инструменты](#Инструменты)
11. [Разное](#Разное)

---


## ES2015: то, что действительно нужно
Перед тем, как вы утоните с головой в пучине вод React самое полезное, что вы можете сделать – изучить некоторые возможности ES2015, которыми вы будете пользоваться постоянно.
* [Блочные зоны видимости](http://jsraccoon.ru/es6-block-scoped-declarations) [**RU**] – `const`, `let` вместо `var`: в чём разница и где стоит быть осторожным.

* [Стрелочные функции](http://jsraccoon.ru/es6-arrow-functions) [**RU**] – `f => f` вместо `function (f) { return f; }` и как не потерять контекст выполнения функции без использования метода `bind`.

* [Расширение литерала объекта](http://jsraccoon.ru/es6-object-literal) [**RU**] – сокращённые записи свойств и методов в объектах.

* [Деструктуризация объектов и массивов](http://jsraccoon.ru/es6-destructuring) [**RU**] – сокращённая запись обращения к свойствам.

* [Модульная система](https://learn.javascript.ru/modules) [**RU**] – основы использования нативных модулей.

* [Классы](https://learn.javascript.ru/es-class) [**RU**] – работа с прототипами и наследованием в новом стандарте.

* [Интерполяция строк](http://jsraccoon.ru/es6-interpolation) [**RU**] или как забыть про `'hello, ' + userName + '!'`.

* [Новые методы массивов](http://2ality.com/2014/05/es6-array-methods.html) [**EN**]: `Array.from`, `find`, `fill`, `includes` и многие другие.

* Промисы:
  * [Обещание бургерной вечеринки](https://medium.com/web-standards/%D0%BE%D0%B1%D0%B5%D1%89%D0%B0%D0%BD%D0%B8%D0%B5-%D0%B1%D1%83%D1%80%D0%B3%D0%B5%D1%80%D0%BD%D0%BE%D0%B9-%D0%B2%D0%B5%D1%87%D0%B5%D1%80%D0%B8%D0%BD%D0%BA%D0%B8-b0ed209809ab) [**RU**] – основы работы промисов на интересных примерах.

  * [Сборник наиболее необходимых на практике приёмов использования промисов](https://habrahabr.ru/post/311804/) [**RU**]

  * [Онлайн песочница](http://bevacqua.github.io/promisees/) [**EN**] для изучения промисов с визуализацией алгоритма их выполнения. Есть несколько отличных примеров для демонстрации принципов работы и возможность написать код своими руками.


## React: Основы основ
* [Статья из официальной документации Thinking in React](https://habrahabr.ru/post/319134/) [**RU**] про идеологию библиотеки, поможет понять, основные идеи лежащие в основе React.

* [React курс для начинающих](https://www.gitbook.com/book/maxfarseer/react-course-ru/details) [**RU**] – текстовый курс по основам React на русском языке. Научит только самым базовым вещам: работе с компонентами, lifecycle хуками, формами и валидацией пропсов с помощью PropTypes.

* [Все фундаментальные принципы React.js, собранные в одной статье](https://medium.com/@divermak/%D0%B2%D1%81%D0%B5-%D1%84%D1%83%D0%BD%D0%B4%D0%B0%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D0%BF%D1%80%D0%B8%D0%BD%D1%86%D0%B8%D0%BF%D1%8B-react-js-%D1%81%D0%BE%D0%B1%D1%80%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5-%D0%B2-%D0%BE%D0%B4%D0%BD%D0%BE%D0%B9-%D1%81%D1%82%D0%B0%D1%82%D1%8C%D0%B5-ec6a97bfd1bf) [**RU**].

* [React.js for Stupid People](http://blog.andrewray.me/reactjs-for-stupid-people/) [**EN**] – спасёт вас, если вы до сих пор ничего не поняли. Всё максимально доступно для самых чайников. Есть перевод на русский язык – [React.js для глупых людей](https://habrahabr.ru/post/249107/) [**RU**].

* [Абсолютный минимум](http://krasimirtsonev.com/blog/article/The-bare-minimum-to-work-with-React) [**EN**], того что надо знать, чтобы начать работать с React.

* [Modern React with Redux](https://www.udemy.com/react-redux/) [**EN**] – курс по основам React. Подойдёт для всех, кто только начинает своё знакомство с экосистемой React. В ходе первой части курса вы построите приложение для поиска и просмотра видео на YouTube (только React, никаких изысков), во второй части начнёте своё путешествие в страну Redux и создадите приложение с использованием Redux и Google Maps API.

* [React to the Future](http://elijahmanor.com/talks/react-to-the-future/dist/#/) [**EN**] – презентация про то, чем действительно является React и, почему появление библиотеки – это большой шаг вперёд.

* [Объяснение принципов работы пропсов и состояний](https://medium.freecodecamp.com/react-props-state-explained-through-darth-vaders-hunt-for-the-rebels-8ee486576492) [**EN**] в React на примере Дарт Вейдера и повстанцев.

* [Подборка интерактивных примеров](https://edgecoders.com/learning-react-js-is-easier-than-you-think-fbd6dc4d935a) [**EN**], которые помогут разобраться в базовых идеях, лежащих в основе библиотеки.


## Ныряем в React с головой
* [PureComponent в React](https://habrahabr.ru/company/redmadrobot/blog/318222/) [**RU**] – как и зачем применять, разбор отличий от Component.

* [Основы производительности React-приложений](http://blog.csssr.ru/2016/12/07/react-perfomance/) [**RU**] – как правильно работать с `shouldComponentUpdate`.

* [Основы работы с содержимым head](https://habrahabr.ru/post/311964/) [**RU**] в React-приложениях (в том числе и изоморфных) с помощью библиотеки react-helmet.

* [React Lifecycle Methods – how and when to use them](https://engineering.musefind.com/react-lifecycle-methods-how-and-when-to-use-them-2111a1b692b1) [**EN**] – всё про жизненный цикл компонентов в React: подробно о том, как работает каждый метод + разбор ситуаций, в которых может понадобиться каждый хук.

* [Контекст в React](https://www.youtube.com/watch?v=lxq938kqIss) [**EN**] – экспериментальный функционал, на который опираются многие популярные библиотеки (react-redux, react-intl).

* [Компоненты высшего порядка](https://www.youtube.com/watch?v=LTunyI2Oyzw) [**EN**] – руководство по работе с вашими собственными компонентами высшего порядка.

* [Десять мини-паттернов в React](https://hackernoon.com/10-react-mini-patterns-c1da92f068c5) [**EN**]: разбор лучших практик при работе с компонентами.

* Курс [Advanced React and Redux](https://www.udemy.com/react-redux-tutorial/) [**EN**] расскажет про основы тестирования React компонентов, работу с аутентификацией на стороне клиента и сервера и компоненты высшего порядка.

* [Работа с AJAX запросами в React](https://daveceddia.com/ajax-requests-in-react/) [**EN**] — где и когда загружать данные.

* [Работа с анимациями в React](https://www.youtube.com/watch?v=npvQX53YuCs) [**EN**] с помощью ReactCSSTransitionGroup. Если вы видели приложения на React с невероятно крутыми переходами между страницами, то посмотрите, как за пару минут можно прикрутить нечто подобное к себе в проект.


## Робкое знакомство с Redux
* Подробное объяснение [принципов разделения презентационных компонентов и компонентов контейнеров](http://www.kanby.ru/prezentaczionnyij-komponent-i-kontejner-v-react.html) [**RU**] при работе с React и Redux.

* [Подборка 8 вещей](https://www.robinwieruch.de/learn-react-before-using-redux/), которые обязательно надо изучить в React, перед знакомством с Redux. [**EN**]

* [Когда я пойму, что готов к Redux?](https://medium.com/@redlan/%D0%BA%D0%BE%D0%B3%D0%B4%D0%B0-%D1%8F-%D0%BF%D0%BE%D0%B9%D0%BC%D1%83-%D1%87%D1%82%D0%BE-%D0%B3%D0%BE%D1%82%D0%BE%D0%B2-%D0%BA-redux-f3198cc5044), перевод статьи разработчика о том, как понять, что наступило время освоить Redux.

* Лучший способ ознакомиться с Redux — посмотреть [курс от самого создателя (Даниила Абрамова) на egghead.io](https://egghead.io/series/getting-started-with-redux) [**EN**] — 30 видео уроков, в которых покажут не только, как пользоваться библиотекой, но и объяснят принцип её работы (по сути, в ходе курса вы сами напишете свой мини-Redux) + в конце расскажут про связку с React с помощью компонентов из React-redux, объяснят, как создавать компоненты-контейнеры, единственная цель которых передавать данные в другие компоненты, а также, как использовать контексты при работе с React.

* Сразу после курса бегите читать [официальную документацию](http://redux.js.org/) [**EN**]. Документация небольшая по объёму, но проясняет многие детали, которые не смог покрыть курс. Так же существует вольный перевод [документации на русском языке](https://www.gitbook.com/book/rajdee/redux-in-russian) [**RU**].

* Статья [Лучшие практики при работе с Redux](https://medium.com/lexical-labs-engineering/redux-best-practices-64d59775802e) [**EN**] расскажет, как не совершить типичных ошибок: где и как организовать бизнес логику приложения, как правильно работать с асинхронными операциями, как создать архитектуру проекта на Redux и многое другое.


## Продвинутый Redux
* [mergeStateToProps](https://habrahabr.ru/post/314582/) [**RU**] — возможности React Redux, о которых вы не знали (`mapDispatchToProps` на стероидах).

* [Идиоматический Redux](https://egghead.io/courses/building-react-applications-with-idiomatic-redux) [**EN**] – второй курс от создателя Redux (Даниила Абрамова) про продвинутые техники использования библиотеки.

* [Обзор экосистемы Redux](https://medium.com/@denisraslov/the-redux-ecosystem-539c630ec521) [**EN**] — объяснение принципов сосуществования с React, React Router + паттерны работы с асинхронностью и аутентификацией.

* [Пишем всю middleware](https://medium.com/@jihdeh/creating-custom-middleware-in-react-redux-961570459ecb) [**EN**].

* [Асинхронный Redux](https://medium.com/@jtbennett/asynchronous-actions-in-redux-8412cf92a26f) [**EN**] – разбор библиотек для работы с асинхронными операциями в Redux.


## Роутинг
* [React Router 4](https://habrahabr.ru/post/329996/) [**RU**] – простое объяснение отличий от предыдущих весрсий.

* [React router + browserHistory](https://www.youtube.com/watch?v=cdUyEou0LHg) [**EN**] – как правильно использовать в продакшене.

* [Всё о React Router 4](https://css-tricks.com/react-router-4/) [**EN**] – подробно о новых идеях заложенных в новой версии библиотеки и почему всё так кардинально изменилось.

* Напиши свой React Router, или [как работает четвёртая версия React Router изнутри](https://tylermcginnis.com/build-your-own-react-router-v4/) [**EN**] – лучший способ понять принцип работы React Router.

* [Изоморфные приложения на React с React Router 4 версии](https://ebaytech.berlin/universal-web-apps-with-react-router-4-15002bb30ccb) [**EN**] – как организовать server-side рендеринг приложения.

* React Router не всегда идеальное решение для организации роутинга. Facebook, например, вообще не использует его в своих проектах. [Обзор альтернатив React Router](https://auth0.com/blog/react-router-alternatives/) [**EN**].

* [Как написать свой роутер](https://hackernoon.com/routing-in-react-the-uncomplicated-way-b2c5ffaee997) [**EN**] – руководство по созданию собственного роутера, работающего с server-side рендерингом.

* [Анимированные переходы между страницами + React Router 4](https://hackernoon.com/animated-page-transitions-with-react-router-4-reacttransitiongroup-and-animated-1ca17bd97a1a) [**EN**] – введение в использование ReactTransitionGroup.


## Архитектура приложения
* [Как избежать излишней сложности состояния приложения](https://habrahabr.ru/post/316070/) [**RU**] – руководство по правильной организации Redux-стора в больших приложениях.

* [Как правильно организовать архитектуру большого приложения на React и Redux](https://www.sitepoint.com/organize-large-react-application/) [**EN**].

* [Пять советов по работе с Redux в больших приложениях](https://techblog.appnexus.com/five-tips-for-working-with-redux-in-large-applications-89452af4fdcb) [**EN**] – продвинутое использование селекторов, техники разделения состояния, переиспользование редюсеров.

## От и до: уроки по созданию полноценных приложений
* [Создаём клон Trello](https://habrahabr.ru/post/308056/) [**RU**]. Описывается разработка сайта c авторизацией и функционалом популярного. Помимо React используется Redux, PostgreSQL, Phoenix (фреймворк для Elixir, который в свою очередь работает на Erlang VM).

* Собираем с нуля изоморфное приложение – пошаговое руководство по настройке сборки приложения на React с server-side рендерингом [**RU**]:
  * [Часть 1](https://habrahabr.ru/post/309958/)
  * [Часть 2](https://habrahabr.ru/post/310284/)
  * [Часть 3](https://habrahabr.ru/post/310952/)

* [Создаём клон Реддита](https://www.sitepoint.com/reddit-clone-react-firebase/) [**EN**] с помощью React и Firebase

* [Создаём клон Твиттера](https://scotch.io/tutorials/build-a-twitter-like-search-feed-with-react-js-and-appbase-io) [**EN**] на React с использованием appbase в качестве бэкенда.

* Создаём медиа-библиотеку с помощью React, Redux и Redux-saga [**EN**]:
  * [Часть 1](https://scotch.io/tutorials/build-a-media-library-with-react-redux-and-redux-saga-part-1)
  * [Часть 2](https://scotch.io/tutorials/build-a-media-library-with-react-redux-and-redux-saga-part-2)


## Тестирование
* [Тестирование компонентов в React](https://medium.freecodecamp.com/the-right-way-to-test-react-components-548a4736ab22) [**EN**]: как сделать это правильно и что нужно тестировать в первую очередь.

* [Лучшие практики тестирования React компонентов](https://medium.com/selleo/testing-react-components-best-practices-2f77ac302d12) [**EN**].

* [Видео курс от egghead.io](https://egghead.io/lessons/javascript-test-javascript-with-jest?pl=testing-javascript-with-jest-a36c4074) [**EN**] про тестирование React приложения с Jest.

* [Руководство по использованию TDD подхода при разработке React приложений](https://www.spencerdixon.com/blog/test-driven-react-tutorial.html) [**EN**]


## Инструменты
* [Webpack + React](https://habrahabr.ru/post/308926/) [**RU**] – как уменьшить бандл в 15 раз: подборка плагинов для экстремального сжатия.

* [Webpack 2 для самых глупых](https://www.sitepoint.com/beginners-guide-to-webpack-2-and-module-bundling/) [**EN**] – подробное введение в использование второй версии сборщика.

* [Видео курс](https://www.youtube.com/playlist?list=PLkEZWD8wbltnRp6nRR8kv97RbpcUdNawY) [**EN**] по второй версии Webpack. Расскажут, как написать базовый конфиг, работать с лоадерами и плагинами, автоматически генерировать HTML, работать с React и Babel, стилями и другими файлами + подробно про настройку Webpack dev server для удобной горячей перезагрузки.

* [Собираем React приложение с помощью Webpack 2 и Babel](https://scotch.io/tutorials/setup-a-react-environment-using-webpack-and-babel) [**EN**] – руководство по настройке самых необходимых инструментов.

* [Code Splitting](http://mxstbr.blog/2016/01/react-apps-with-pages/) [**EN**] в React приложении – разделение большого бандла на меньшие части для более быстрой загрузки приложения.

* [Горячая перезагрузка всего!](https://hackernoon.com/hot-reload-all-the-things-ec0fed8ab0) [**EN**] Как использовать Hot Module Replacement в Webpack для перезагрузки фронтенда и бэкенда в изоморфном приложении.

* [Руководство по настройке редактора кода Atom](https://medium.com/productivity-freak/my-atom-editor-setup-for-js-react-9726cd69ad20) [**EN**] для наиболее продуктивной работы с React приложениями.


## Разное
* [Подборка 15 вопросов с собеседования](http://www.kanby.ru/voprosyi-pro-react-na-sobesedovanii.html) [**RU**] для React-разработчика.

* [Подборка интересных open source проектов](https://www.reddit.com/r/reactjs/comments/496db2/large_open_source_reactredux_projects/) [**EN**] сделанных на React. На их примере можно посмотреть, как правильно организовать код в своих проектах и подглядеть пару интересных инструментов для сборки.

* [Awesome React Talks](https://github.com/tiaanduplessis/awesome-react-talks) [**EN**] – подборка лучший докладов с конференций, посвященных React, всё разделено по годам.

* [React за 30 минут](https://www.youtube.com/watch?v=_MAD4Oly9yg) [**EN**] – создайте свой клон библиотеки и посмотрите, как всё устроено изнутри.

* [Основы работы с recompose](https://www.youtube.com/watch?v=SQtrgiLy3Fo) [**EN**] – библиотекой для расширения возможностей функциональных компонентов и их оптимизации.

* [Шпаргалка по принципам работы с экосистемой React + Redux](https://github.com/uanders/react-redux-cheatsheet) [**EN**] в виде диаграммы.
