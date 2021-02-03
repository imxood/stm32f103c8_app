## 编译, 烧写

    west build -b stm32f103c8 stm32f103c8_app -- -DBOARD_ROOT=. -DCMAKE_EXPORT_COMPILE_COMMANDS=ON
    west build
    west flash