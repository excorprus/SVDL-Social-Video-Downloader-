# 🎬 SVDL - Social Video Downloader
Десктопное приложение для скачивания видео с YouTube, VK, Rutube, TikTok, Twitch и других платформ на базе `yt-dlp`.

## ✨ Возможности
-  Очередь загрузок с управлением паузой/возобновлением
- 🎛 Выбор качества и формата с отображением размера файла
- 📁 Автоматическая сортировка по папкам платформ
- 🌙 Светлая/тёмная тема + RU/EN локализация
- 🍪 Поддержка `cookies.txt` для приватных видео
- 📦 Готовые установщики Windows (Installer + Portable)

## 📥 Установка
1. Перейдите в раздел [Releases](https://github.com/yourname/svdl-downloader/releases)
2. Скачайте `SVDL-Setup-v 1.0.0.exe
3. Запустите и пользуйтесь. Требуется Windows 10/11 x64.

## 🛠 Запуск из исходников
```bash
git clone https://github.com/yourname/svdl-downloader.git
cd svdl-downloader
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python src/main.py
