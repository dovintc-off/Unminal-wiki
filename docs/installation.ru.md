# Начало работы с Unminal Engine

!!! Предупреждение "Системные требования"
    - __Операционная система:__ Windows 10 или новее
    - __Необходимое ПО:__ [.NET SDK](https://dotnet.microsoft.com/download)
    - __Гайд по установке .NET:__ [Microsoft Learn](https://learn.microsoft.com/ru-ru/dotnet/core/install/windows)

---

##  Установка Движка

Есть два способа установки:

### Способ №1: Установка через Git (Рекомендуется)

Этот способ позволит вам легко обновлять проект в будущем.

1. __Установите Git__ с [официального сайта](https://git-scm.com/install/windows)

2. __Откройте терминал__ (PowerShell или Командную строку)

3. __Клонируйте репозиторий:__
``` bash
git clone https://github.com/dovintc-off/Unminal-Engine.git
```

4. __Перейдите в папку:__
``` bash
cd Unminal-Engine
```

5. __Запомните путь__ к папке - это нужно чтобы открыть папку в IDE (для VScode можно использовать в том же терминале команду `code .`)

> __Преимущество:__ Простое обновление проекта, используя `git pull`

---

### Способ №2: скачивание ZIP Архива

Простой способ быстро приступить к работе без использования Git.

1. Скачайте архив со [страницы репозитория](https://github.com/dovintc-off/Unminal-Engine)

2. Нажмите зелёную кнопку __"<> Code"__

3. Выберите вариант __"Download ZIP"__ из выпадающего меню

4. После скачивания, распакуйте архив в удобную для вас папку

!!! tip Программы для распаковки архивов
    - Windows 11: встроенная поддержка ZIP файлов
    - Windows 10 и ранее: 
        - [7-Zip](https://www.7-zip.org/) (Бесплатный, рекомендуется)
        - [WinRAR](https://www.win-rar.com/predownload.html)

---

## Запуск и редактирование кода.

### Рекомендуемые IDE (среда разработки)

| IDE | ссылка | Описание |
|-----|------|------|
| __Visual Studio Code__ | [Download](https://code.visualstudio.com/download) | Легкий, нужны расширения |
| __Visual Studio 2022__ | [Download](https://visualstudio.microsoft.com/downloads/) | полная поддержка IDE от Microsoft |
| __JetBrains Rider__ | [Download](https://www.jetbrains.com/rider/download/?section=windows) | кросс-платформенное IDE для .NET |

### Настройка Visual Studio Code

Если вы выбрали VS Code, установите следующие расширения:

1. __C# Dev Kit__ - поддержка C#
2. __.NET Install Tool__ - управление .NET SDK
3. __IntelliCode for C#__ - Улучшенные подсказки IntelliSense
4. __GitLens__ - интеграция с Git (если вы использовали первый способ установки.)

> __Совет:__ Для более быстрой навигации используйте `Ctrl + Click`, чтобы перейти к определениям методов и классов.

---

## Первый запуск

1. Откройте папку проекта в выбранной вами IDE
2. Дождитесь восстановления зависимостей NuGet
3. Найдите файл решения `.sln` или файл проекта `.csproj`
4. Нажмите __F5__ или кликтните на кнопу __`Run`__