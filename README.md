# mesa-20.1.5_v2_ubuntu-19.04\20.04\20.10 X86_64 graphics support fedora libc-2.32<==fedora==>33
graphics , mesa , 20.1.5 , support , x86_64 , gallium-pipe , OpenCL , d3d , nine , vdpau , libGLX_indirect , linux , ubuntu 20.04 , ubuntu 19.04 , EGL1.4 , not freeze game play steam wayland session , libc-2.31 , old stable video driver , самая лучшая в мире гамма и цветовая контрастность в браузерах , best color gamma in browsers

Ubuntu X64 ubuntu 19.04 disco dingo , ubuntu 20.04 focal fossa , Ubuntu 20.10 Groovy Gorilla , not test support ubuntu 18.10.19.10 , alternative driver libglu драйвер работает даже если вы его установите и поверх новой версии mesa тем самым заменив её.

1) install https://github.com/Griggorii/mesa-20.1.2_V15-libdrm_ubuntu-19.04-20.04-20.10_X86_64_full_stack_graphics + libswrAVX.so.0.0.0 , libswrAVX2.so.0.0.0

2) sudo tar xvpf mesa-20.1.5_by_grigorii_v2.tar.xz -C /

Terminal run check version command:

$ glxinfo

Reboot enjoy test wayland 8K https://www.youtube.com/watch?v=gYO1uk7vIcc если конечно оператор не жадный уже 8K не на иксах

Драйвер был получен методом чрута в моей специальной системе продемонстрирована она тут https://t.me/java_8_oracle_X64_Griggorii/2 в отличии от предыдущего имеет меньший размер ну естественно потому что на видео показано что у меня система модифицированная , а gcc я ссыльно перебросил с 9.30 на 10 так же как и llvm https://github.com/Griggorii/llvm-10-tools в плане производительности может быть чуть медленее чем без v2(но не точно может быть и наоборот)  , но контрастнее на это и уходит чуть больше производительности за счет этого улучшается даже самое холеное видео изображение так что если у вас компьютер мощный то этот драйвер будет рисовать лучше , если видео карта и компьютер слабый и тем более wayland то используйте без v2 отсюда https://github.com/Griggorii/mesa-20.1.5_ubuntu-19.04-20.04-20.10_X86_64_graphics.

Griggorii@gmail.com
