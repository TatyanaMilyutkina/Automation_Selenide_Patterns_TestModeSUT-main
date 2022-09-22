# Automation_Selenide_Patterns_TestModeSUT 

[![Build status](https://ci.appveyor.com/api/projects/status/keil756h4y3nmvf7?svg=true)](https://ci.appveyor.com/project/TatyanaMilyutkina/automation-selenide-patterns-testmodesut-main)

# Обучение в Нетологии.

## Курс Автоматизированное тестирование

## Тема: Patterns
Тестирование функции входа через Web интерфейс(приложение ```app-ibank.jar```) с использованием Selenide

Написание тестов с условиями:

- наличие пользователя;
- статус пользователя;
- невалидный логин;
- невалидный пароль и тд.

**Для запуска проекта:**
1. Склонировать проект из репозитория командой 

```
git clone https://github.com/holyblaz/Automation_Selenide_Patterns_TestModeSUT.git
``` 
2. Открыть склонированный проект в Intellij IDEA
3. Открыть в терминале каталог ```artifacts```
4. Для запуска приложения в тестовом режиме ввести команду ```java -jar ./app-ibank.jar -P:profile=test```
5. Для запуска в браузере ввести ссылку  http://localhost:9999/
6. Запустить команду ```./gradlew test```
