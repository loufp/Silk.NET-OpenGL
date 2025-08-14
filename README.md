# Silk.NET OpenGL Пример

Этот проект демонстрирует использование **Silk.NET** для создания окна, загрузки OpenGL-контекста и рендеринга простого квадрата с помощью **VAO, VBO, EBO** и шейдеров.  
Код написан на **C#** и работает кроссплатформенно (Windows, Linux, macOS).

## 📌 Функционал
- Создание окна с помощью [`Silk.NET.Windowing`](https://github.com/dotnet/Silk.NET)
- Обработка ввода с клавиатуры через `Silk.NET.Input`
- Настройка и использование **VAO** (Vertex Array Object)
- Загрузка вершин в **VBO** (Vertex Buffer Object)
- Использование **EBO** (Element Buffer Object) для индексации вершин
- Компиляция и линковка вершинного и фрагментного шейдера
- Рендеринг квадрата с использованием OpenGL

## 🎮 Управление
- `Esc` — закрыть окно

## 🚀 Запуск
1. Установите [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
2. Склонируйте репозиторий:
   ```bash
   git clone https://github.com/username/repository.git
