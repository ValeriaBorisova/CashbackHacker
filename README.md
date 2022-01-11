[![Tests](https://github.com/ValeriaBorisova/CashbackHacker/actions/workflows/gradle.yml/badge.svg)](https://github.com/ValeriaBorisova/CashbackHacker/actions/workflows/gradle.yml)

* Task description 

``` https://github.com/netology-code/aqa-homeworks/tree/master/basics```

________

Task №1 - TestNG

Реализация проекта:
* Создана ветка ```testng``` 
* Добавлены в зависимости TestNG:

  ``` 
  dependencies {
      testImplementation 'org.testng:testng:7.1.0'
   }
    test {
         useTestNG()
    }

```

* Написаны автотесты
* Подключен и адаптирован CI ``` Gradle.yml``` через Github Actions
