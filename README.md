# Видеоплеер  
Удобный инструмент для просмотра видео.  

![image](https://github.com/user-attachments/assets/56864402-f961-40b9-bcbd-97ca11fb9cee)


## Функционал
Плеер оснащён панелью управления с основными функциями:  
- Воспроизведение и пауза  
- Включение и отключение звука  
- Переключение в полноэкранный режим  

## Выбор видео  
Плеер создан на основе библиотеки, описанной в [документации](https://github.com/devmanorg/video-player-jslib/blob/master/README.md).  

По умолчанию воспроизводится видео по [этой ссылке](https://dvmn.org/media/filer_public/78/db/78db3456-3fd3-4504-9ed9-d2d1fd843c0b/highest_peak.mp4).  

Для загрузки другого видео можно передать ссылку через параметр `src` (ссылки должны заканчиваться на формат файла):  
```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
});
</script>
```

## Демонстрация
Работающий плеер доступен [здесь](https://gont1errr.github.io/video-player-jslib/).  
