# React Things
Коллекция материалов для изучения ES2015, React, Redux, Webpack, Babel и всего остального.


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
* [Статья из официальной документации Thinking in React](https://facebook.github.io/react/docs/thinking-in-react.html) [**EN**] про идеологию библиотеки, поможет понять, основные идеи лежащие в основе React.

* [Modern React with Redux](https://www.udemy.com/react-redux/) [**EN**] – курс по основам React. Подойдёт для всех, кто только начинает своё знакомство с экосистемой React. В ходе первой части курса вы построите приложение для поиска и просмотра видео на YouTube (только React, никаких изысков), во второй части начнёте своё путешествие в страну Redux и создадите приложение с использованием Redux и Google Maps API.

* [React to the Future](http://elijahmanor.com/talks/react-to-the-future/dist/#/) [**EN**] – презентация про то, чем действительно является React и, почему появление библиотеки – это большой шаг вперёд.

* [React курс для начинающих](https://www.gitbook.com/book/maxfarseer/react-course-ru/details) [**RU**] – текстовый курс по основам React на русском языке. Научит только самым базовым вещам: работе с компонентами, lifecycle хуками, формами и валидацией пропсов с помощью PropTypes.

* [React.js for Stupid People](http://blog.andrewray.me/reactjs-for-stupid-people/) [**EN**] – спасёт вас, если вы до сих пор ничего не поняли. Всё максимально доступно для самых чайников. Есть перевод на русский язык – [React.js для глупых людей](https://habrahabr.ru/post/249107/) [**RU**].

## Ныряем в React с головой
* [React Lifecycle Methods – how and when to use them](https://engineering.musefind.com/react-lifecycle-methods-how-and-when-to-use-them-2111a1b692b1) [**EN**] – всё про жизненный цикл компонентов в React: подробно о том, как работает каждый метод + разбор ситуаций, в которых может понадобиться каждый хук.

* [PureComponent в React](https://habrahabr.ru/company/redmadrobot/blog/318222/) [**RU**] – как и зачем применять, разбор отличий от Component.

* [Контекст в React](https://www.youtube.com/watch?v=lxq938kqIss) [**EN**] – экспериментальный функционал, на который опираются многие популярные библиотеки (react-redux, react-intl).

* [Компоненты высшего порядка](https://www.youtube.com/watch?v=LTunyI2Oyzw) [**EN**] – руководство по работе с вашими собственными компонентами высшего порядка.

* [Основы производительности React-приложений](http://blog.csssr.ru/2016/12/07/react-perfomance/) [**RU**] – как правильно работать с `shouldComponentUpdate`.

* [Десять мини-паттернов в React](https://hackernoon.com/10-react-mini-patterns-c1da92f068c5) [**EN**]: разбор лучших практик при работе с компонентами.

* Курс [Advanced React and Redux](https://www.udemy.com/react-redux-tutorial/) [**EN**] расскажет про основы тестирования React компонентов, работу с аутентификацией на стороне клиента и сервера и компоненты высшего порядка.

## Робкое знакомство с Redux
* Лучший способ ознакомиться с Redux — посмотреть [курс от самого создателя (Даниила Абрамова) на egghead.io](https://egghead.io/series/getting-started-with-redux) [**EN**] — 30 видео уроков, в которых покажут не только, как пользоваться библиотекой, но и объяснят принцип её работы (по сути, в ходе курса вы сами напишете свой мини-Redux) + в конце расскажут про связку с React с помощью компонентов из React-redux, объяснят, как создавать компоненты-контейнеры, единственная цель которых передавать данные в другие компоненты, а также, как использовать контексты при работе с React.

* Сразу после курса бегите читать [официальную документацию](http://redux.js.org/) [**EN**]. Документация небольшая по объёму, но проясняет многие детали, которые не смог покрыть курс.

* Статья [Лучшие практики при работе с Redux](https://medium.com/lexical-labs-engineering/redux-best-practices-64d59775802e) [**EN**] расскажет, как не совершить типичных ошибок: где и как организовать бизнес логику приложения, как правильно работать с асинхронными операциями, как создать архитектуру проекта на Redux и многое другое.

* Подробное объяснение [принципов разделения презентационных компонентов и компонентов контейнеров](http://www.kanby.ru/prezentaczionnyij-komponent-i-kontejner-v-react.html) [**RU**] при работе с React и Redux.

## Продвинутый Redux
* [Пишем всю middleware](https://medium.com/@jihdeh/creating-custom-middleware-in-react-redux-961570459ecb) [**EN**].

* [Асинхронный Redux](https://medium.com/@jtbennett/asynchronous-actions-in-redux-8412cf92a26f) [**EN**] – всё, что нужно знать про работу с асинхронными операциями.

## Архитектура приложения
* [Как правильно организовать архитектуру большого приложения на React и Redux](https://www.sitepoint.com/organize-large-react-application/) [**EN**].

* [Как избежать излишней сложности состояния приложения](https://habrahabr.ru/post/316070/) [**RU**] – руководство по правильной организации Redux-стора в больших приложениях.

## Роутинг
* Напиши свой React Router, или [как работает четвёртая версия React Router изнутри](https://tylermcginnis.com/build-your-own-react-router-v4/) [**EN**] – лучший способ понять принцип работы React Router.

* [Изоморфные приложения на React с React Router 4 версии](https://ebaytech.berlin/universal-web-apps-with-react-router-4-15002bb30ccb) [**EN**] – как организовать server side рендеринг приложения.

* React Router не всегда идеальное решение для организации роутинга. Facebook, например, вообще не использует его в своих проектах. [Обзор альтернатив React Router](https://auth0.com/blog/react-router-alternatives/).

## Тестирование
* [Тестирование компонентов в React](https://medium.freecodecamp.com/the-right-way-to-test-react-components-548a4736ab22) [**EN**]: как сделать это правильно и что нужно тестировать в первую очередь.

* [Лучшие практики тестирования React компонентов](https://medium.com/selleo/testing-react-components-best-practices-2f77ac302d12) [**EN**].

## Инструменты
* [Собираем React приложение с помощью Webpack 2 и Babel](https://scotch.io/tutorials/setup-a-react-environment-using-webpack-and-babel) [**EN**] – руководство по настройке самых необходимых инструментов.

* [Code Splitting](http://mxstbr.blog/2016/01/react-apps-with-pages/) в React приложении – разделение большого бандла на меньшие части для более быстрой загрузки приложения.

## От и до: уроки по созданию полноценных приложений
* Создаём медиа библиотека с помощью React, Redux и Redux-saga [**EN**]:
  * [Часть 1](https://scotch.io/tutorials/build-a-media-library-with-react-redux-and-redux-saga-part-1)
  * [Часть 2](https://scotch.io/tutorials/build-a-media-library-with-react-redux-and-redux-saga-part-2)

## Разное
* [Подборка 15 вопросов с собеседования](http://www.kanby.ru/voprosyi-pro-react-na-sobesedovanii.html) [**RU**] для React-разработчика.

* [Многофакторная аутентификация и React](https://scotch.io/tutorials/multifactor-authentication-in-your-react-apps) [**EN**].
