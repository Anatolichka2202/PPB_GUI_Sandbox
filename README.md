# PPB_GUI_Sandbox

Исторический эксперимент интерфейса ППБ. **Этот отдельный репозиторий не является действующим GUI внутри PPB_Project.**

Корневая сборка создаёт простое приложение из `main.cpp` и `mainwindow.*`. Старые виджеты в `gui/` этой целью не подключаются.

Объявленные требования: CMake 3.16+, C++17, Qt5/Qt6 Widgets.

```sh
cmake -S . -B build -DCMAKE_PREFIX_PATH=/path/to/Qt
cmake --build build
```

Сборка здесь не воспроизводилась. Поддерживаемый продукт: [PPB_Project](https://github.com/Anatolichka2202/PPB_Project), включая его собственный подкаталог `PPB_GUI_Sandbox`.
