Консольный калькулятор.
Калькулятор поддерживает следующие действия: сложение, вычитание, умножение, деление и возведение в степень

Для сборки с динамической библиоткой выполнить комадны:
cmake -B build -DENABLE_CLANG_FORMAT=ON -DENABLE_CLANG_TIDY=ON;
cmake --build build;
cmake --build build --target install;

Для сборки со статической библиотекой выполнить те же комады, но используя файл CMakeLists.txt из папки CMake_for_static_lib
