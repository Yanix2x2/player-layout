# Видеоплеер на базе Playable.js

Этот проект представляет собой простой видеоплеер, созданный с использованием библиотеки Playable.js.

![Screenshot]

Элементы управления:
- Кнопки Play/Pause
- Кнопки включения/выключения звука
- Кнопка полноэкранного режима

## GitHub Pages deployments

[Ссылка](https://yanix2x2.github.io/player-layout/)

## Использование
1. JS код поставляется в виде одного файла `player.js`
2. Для работы код требует двух библиотек:
- jQuery 
- Playable.js
3. Обновите атрибут `src` в функции `createPlayer`, чтобы указать на ваш желаемый видеофайл
```html
<script type="text/javascript">
  createPlayer({
    elementId: 'player',
    src: 'https://dvmn.org/media/filer_public/d0/16/d016d9b8-4180-4bb9-ad83-0241f61627b8/samsung_demo_-_alive_in_color.mp4'
});
</script>
```
4. Откройте HTML-файл в веб-браузере, чтобы просмотреть и взаимодействовать с видеоплеером

