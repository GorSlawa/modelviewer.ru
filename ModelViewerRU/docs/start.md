## Быстрый старт:


```html
<!-- Подключение библиотеки model-viewer -->
<script type="module" src="https://ajax.googleapis.com/ajax/libs/model-viewer/3.5.0/model-viewer.min.js"></script>

<!-- Блок HTML кода для отображения 3D модели  -->
<model-viewer 
alt="Космический костюм Нила Армстронга из Смитсоновского офиса 
программ оцифровки и Национального музея авиации и космонавтики" 
src="shared-assets/models/NeilArmstrong.glb" 
ar 
environment-image="shared-assets/environments/moon_1k.hdr" 
poster="shared-assets/models/NeilArmstrong.webp" 
shadow-intensity="1" 
camera-controls 
touch-action="pan-y">
</model-viewer>

```

##### Описание тегов:
(схоже с тегом img)

- alt - альтернативное описание словами, если браузер не сможет отобразить содержимое 
- src - путь к 3D модели 
