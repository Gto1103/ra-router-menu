[![Build status](https://ci.appveyor.com/api/projects/status/8v0x9q4ql1fxdx2l?svg=true)](https://ci.appveyor.com/project/Gto1103/ra-router-menu)

[Страница проекта](https://gto1103.github.io/ra-router-menu/)

# Навигационное меню

Необходимо реализовать меню для сайта гоночного такси с пунктами «Главная», «Дрифт-такси», «Time Attack» и «Forza Karting». При переходе на страницу соответствующий пункт меню должен подсветиться:

![Навигационное меню](https://github.com/netology-code/ra16-homeworks/raw/master/router/menu/assets/menu.jpg)

## Описание компонента

Компонент должен создавать HTML-разметку вида:

```html
<nav class="menu">
  <a class="menu__item" href="/">Главная</a>
  <a class="menu__item" href="/drift">Дрифт-такси</a>
  <a class="menu__item" href="/timeattack">Time Attack</a>
  <a class="menu__item" href="/forza">Forza Karting</a>
</nav>
```

Активный пункт меню помечается классом `menu__item-active`.

## Реализация

Необходимо реализовать компонент `Menu`.

Воспользуйтесь готовым файлом `App.js` и стилями `css/index.css` из каталога в качестве отправной точки. Замените ими те, что создаются в create-react-app.

**Обратите внимание**: в файлах `App.js` расположено несколько компонентов не потому, что так нужно делать, а чтобы вам было удобнее копировать. Будет хорошо, если в своём решении вы разнесёте их по разным файлам.
