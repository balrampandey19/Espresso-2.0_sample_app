# Android UI testing framework

<img align="center" src='https://lh5.googleusercontent.com/-E2YPLlVAl0U/VJUcPrgVC-I/AAAAAAAAGFM/AkqZn5N8rrc/w890-h1009/espresso_lockup.png' width='100' height='200'/>


Espresso is a testing framework for Android to make it easy to write reliable user interface tests.

Google released the Espresso framework in Oct. 2013. Since its 2.0 release Espresso is part of the Android Support Repository.

Espresso automatically synchronizes your test actions with the user interface of your application. The framework also ensures that your activity is started before the tests run. It also let the test wait until all observed background activities have finished.

It is intended to test a single application but can also be used to test across applications. If used for testing outside your application, you can only perform black box testing, as you cannot access the classes outside of your application.

Espresso has basically three components:

ViewMatchers - allows to find view in the current view hierarchy

ViewActions - allows to perform actions on the views

ViewAssertions - allows to assert state of a view





http://www.vogella.com/tutorials/AndroidTestingEspresso/article.html

https://developer.android.com/training/testing/ui-testing/espresso-testing.html

https://google.github.io/android-testing-support-library/docs/espresso/cheatsheet/

https://www.youtube.com/watch?v=TGU0B4qRlHY


