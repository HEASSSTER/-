# Погода (PWA)

## Как выложить на GitHub Pages
1. Создайте репозиторий на github.com и загрузите в него все файлы из этой папки.
2. Settings → Pages → Source: Deploy from a branch → ветка main, папка / (root).
3. Через минуту сайт будет доступен по адресу https://ИМЯ.github.io/РЕПОЗИТОРИЙ/
4. Откройте адрес в Chrome на телефоне: меню → «Установить приложение».

## Как собрать APK
- Самый простой путь: https://www.pwabuilder.com — вставьте адрес сайта и выберите Android. Сервис соберёт проект, подписанный APK или AAB.
- Или Bubblewrap (npm i -g @bubblewrap/cli, затем bubblewrap init --manifest=АДРЕС/manifest.webmanifest и bubblewrap build). Нужны Node.js, JDK и Android SDK.
- Для Google Play понадобится аккаунт разработчика и привязка сайта через assetlinks.json.

## Файлы
index.html — приложение, manifest.webmanifest — описание для установки, sw.js — офлайн-режим, icon-*.png — иконки.
