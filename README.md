# Разработка под Android - Технотрек открытый курс

[Описание курса и список всех лекций на Habrahabr](https://habrahabr.ru/company/mailru/blog/345252/)

Здесь собраны ссылки на репозитории с исходным кодом приложений, которые использовались на лекциях для демонстрации, а так же ссылки на дополнительные материалы, рекомендованные для прочтения.

## Лекция №1

В этой лекции использовалось приложение созданное с помощью визарда в Android Studio, поэтому нет смысла его выкладывать.
### Дополнительные материалы
В качестве дополнительных материалов мы рекомендуем несколько книг по разработке на Java, с которыми полезно ознакомиться перед началом изучения курса.

[Java. Библиотека профессионала. Автор К. Хорстманн (Core Java by K. Horstamnn)](https://www.amazon.com/Core-Java-I-Fundamentals-10th/dp/0134177304)

[Java. Эффективное программирование. Автор Д. Блох (Effective Java by Joshua Bloch)](https://www.amazon.com/Effective-Java-3rd-Joshua-Bloch/dp/0134685997)

[Java Concurrency in Practice by Brian Goetz](https://www.amazon.com/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601)

## Лекция №2
### Демонстрационное приложение
[Простейшие UI элементы и Fragments](https://bitbucket.org/ybereza/technoparklection2.git)
Этот проект использовался в нескольких лекциях. Для вас, на данный момент, важны лишь StartActivity, UIElements, LayoutActivity (тут вы можете заодно посмотреть как через Intent передавать дополнительные данные), FragmentActivity с SimpleFragment и SimpleDialogFragment.
### Дополнительные материалы
<a target="_blank" href="https://developer.android.com/guide/components/activities/activity-lifecycle.html">Activity Lifecycle</a>

<a target="_blank" href="https://developer.android.com/guide/components/intents-filters.html">Intents and intent filters</a>

<a target="_blank" href="https://developer.android.com/guide/components/fragments.html?hl=ru">Fragments</a>

<a target="_blank" href="https://android-developers.googleblog.com/2012/05/using-dialogfragments.html">DialogFragment</a>

<a target="_blank" href="https://developer.android.com/guide/topics/ui/declaring-layout.html">Android Layout (Макеты или разметка)</a>

<a target="_blank" href="https://android-school.ru/%D1%83%D1%80%D0%BE%D0%BA-3-%D0%B2%D0%B5%D1%80%D1%81%D1%82%D0%BA%D0%B0-%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%BE%D0%B2-%D0%B2%D0%B8%D0%B4%D1%8B-layout/">Linear Layout и Frame Layout</a>

<a target="_blank" href="https://android-school.ru/%D1%83%D1%80%D0%BE%D0%BA-4-relativelayout/">Relative Layout</a>

<a target="_blank" href="https://android-school.ru/%D1%83%D1%80%D0%BE%D0%BA-5-textview-button-%D0%B2%D0%B7%D0%B0%D0%B8%D0%BC%D0%BE%D0%B4%D0%B5%D0%B9%D1%81%D1%82%D0%B2%D0%B8%D0%B5-%D1%81-%D1%8D%D0%BB%D0%B5%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D0%BC%D0%B8/">TextView и Button</a>

## Лекция №3
### Демонстрационное приложение
[Пример concurrency](https://github.com/kirillF/Track4Demo)

[Пример Android Permissions](https://github.com/kirillF/permission-demo)
### Дополнительные материалы
[Материалы по concurrency](https://docs.oracle.com/javase/tutorial/essential/concurrency/)

[Документация по Android Permissions](https://developer.android.com/guide/topics/permissions/index.html)

## Лекция №4
### Демонстрационное приложение
[Пример с Socket, UrlConnection, org.json](https://github.com/ybereza/httpsample)

[Пример с авторизацией на GitHub, GSON, OkHttp, UrlConnection](https://github.com/kirillF/oauth-demo)
### Дополнительные материалы
<a target="_blank" href="https://github.com/google/gson">Офицальный сайт GSON</a>

<a target="_blank" href="http://guides.codepath.com/android/leveraging-the-gson-library">GSON Tutorial</a>

<a target="_blank" href="https://github.com/square/okhttp/wiki">Раздел Wiki по OkHttp</a>

<a target="_blank" href="https://guides.codepath.com/android/Using-OkHttp">Использование OkHttp</a>

<a target="_blank" href="http://square.github.io/retrofit/">Сайт c Retrofit</a>

<a target="_blank" href="https://guides.codepath.com/android/Consuming-APIs-with-Retrofit">Использование Retrofit</a>

## Лекция №5
### Демонстрационное приложение
[Проект с сервисами. Смотрите классы ServiceActivity, TestService, CommandService](https://bitbucket.org/ybereza/technoparklection2)

[Проект с использованием Job Scheduler](https://github.com/kirillF/JobSchedulerDemo)
### Дополнительные материалы
<a target="_blank" href="https://developer.android.com/guide/components/services.html">Сервисы</a>

<a target="_blank" href="http://www.vogella.com/tutorials/AndroidServices/article.html">Android Services Tutorial</a>

<a target="_blank" href="https://guides.codepath.com/android/Using-the-RecyclerView">Recycler View</a>

## Лекция №6
### Демонстрационное приложение
[Пример с использованием Storage и LRU Cache](https://github.com/ybereza/Lection8)

[Пример использования SQLite](https://github.com/ybereza/dbexample)

[Пример исполозования Content Provider](https://github.com/ybereza/Lection9)

## Лекция №7
### Демонстрационное приложение
[Проект с ресурсами](https://github.com/ybereza/Lection6)

[Проект с тестами](https://github.com/ybereza/lecture10)

[Проект с Mockito](https://github.com/kirillF/technotrack-mockito)

## Лекция №8
### Демонстрационное приложение
[Проект с Material Design](https://github.com/ybereza/MaterialDemo)
### Дополнительные материалы
<a target="_blank" href="https://guides.codepath.com/android/Defining-The-ActionBar">ActionBar</a>

<a target="_blank" href="https://guides.codepath.com/android/Using-the-App-Toolbar">ToolBar</a>

<a target="_blank" href="https://guides.codepath.com/android/Floating-Action-Buttons">Floating Action Buttons</a>

<a target="_blank" href="https://guides.codepath.com/android/Handling-Scrolls-with-CoordinatorLayout">Coordinator Layout</a>

## Лекция №9
### Демонстрационное приложение
[Проект с CustomView](https://github.com/ybereza/CustomViewSample)

[Проект с анимациями](https://github.com/ybereza/Lection13)
### Дополнительные материалы
<a target="_blank" href="https://guides.codepath.com/android/Basic-Painting-with-Views">Custom Views</a>

<a target="_blank" href="https://guides.codepath.com/android/Defining-Custom-Views">Использование Custom Views</a>

<a target="_blank" href="https://guides.codepath.com/android/Animations">Анимации</a>

## Лекция №10
### Демонстрационное приложение
[Проект с нотификациями](https://github.com/ybereza/Notifications)

[Проект с виджетами](https://github.com/ybereza/Widgets)
### Дополнительные материалы
<a target="_blank" href="https://medium.com/exploring-android/exploring-android-o-notification-channels-94cd274f604c">Особенности нотификаций в Android 8.0</a>