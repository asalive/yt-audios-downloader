
# Audio downloader

Скачать аудио из YouTube видео. 

Нужно установить одну зависимость: [yt-dlp](https://github.com/yt-dlp/yt-dlp). Версия Python: >= 3.8.

## Использование

Запустить скрипт, передав ссылку на видео в любом формате:

```bash
python main.py <Ссылка на видео>
```

Создаётся папка (название – ID видео), куда сохраняются доступные аудио.

Протестировано только на двух видео:

* [https://youtube.com/watch?v=MY5SatbZMAo](https://youtube.com/watch?v=MY5SatbZMAo)

* [https://www.youtube.com/watch?v=36m1o-tM05g](https://www.youtube.com/watch?v=36m1o-tM05g)
