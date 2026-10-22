# Сторонние компоненты

File flicker использует отдельные инструменты FFmpeg, gifski и pngquant, а также Pillow, FontTools, Brotli, NumPy, ONNX Runtime, Geist и модели BiRefNet Lite и Real-ESRGAN. Версия macOS использует динамические библиотеки Qt/PySide6.

Тексты лицензий и сведения о компонентах включены в установленные приложения. Исходники отдельных CLI-инструментов находятся в source-code/ внутри комплекта; у macOS — в File flicker.app/Contents/Resources/source-code/. Эти компоненты сохраняют собственные условия лицензирования.

Windows: FFmpeg 9.0.2 GPLv3, исходный коммит https://github.com/FFmpeg/FFmpeg/commit/946fcce07b ; оригинальная сборка https://www.gyan.dev/ffmpeg/builds/ . Конфигурация и версии внешних библиотек перечислены в README оригинальной сборки. pngquant 2.18.0/libimagequant 2.18.0 — GPL; gifski 1.34.0 — AGPL-3.0-or-later. Инструменты вызываются отдельными процессами.

macOS: FFmpeg с x264/libvpx/Opus, pngquant/libimagequant, gifski собираются из зафиксированных исходников; архивы, версии и инструкции сборки, включая Rust-зависимости, входят в приложение.

Geist — SIL OFL 1.1. BiRefNet Lite — MIT; Real-ESRGAN — BSD-3-Clause. Qt/PySide6 — условия лицензий соответствующих библиотек, тексты включены; исходники Qt 6.8.3: https://download.qt.io/archive/qt/6.8/6.8.3/ .

Этот репозиторий предназначен для загрузки установщиков и документации приложения.
