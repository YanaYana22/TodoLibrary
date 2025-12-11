# Todo.Core Library

Простая библиотека для управления списком задач.

## Установка через NuGet

### Добавьте источник GitHub Packages в NuGet:

1. Откройте Visual Studio.
2. Перейдите в **Tools → NuGet Package Manager → Package Manager Settings → Package Sources**.
3. Добавьте новый источник:
   - **Name**: `GitHub`
   - **Source**: `https://nuget.pkg.github.com/YanaYana22/index.json`
4. Нажмите **Update**, затем **OK**.

### Установите пакет:

1. Откройте свой проект.
2. Перейдите в **Tools → NuGet Package Manager → Manage NuGet Packages for Solution**.
3. Выберите источник **GitHub**.
4. Найдите пакет **Todo.Core** и установите его.

## Использование

```csharp
using Todo.Core;

var list = new TodoList();
var item = list.Add("Купить молоко");
item.MarkDone();