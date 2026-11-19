LANGE ULTRA CLASSIC — исходный проект циферблата Wear OS

Целевое устройство: Samsung Galaxy Watch Ultra, Wear OS 6.
Формат: Watch Face Format (WFF) v2.

Что включено:
- Чёрный циферблат с металлической шкалой и часовыми метками.
- Аналоговые часы с системными движущимися стрелками.
- Секундная стрелка скрывается в режиме AOD.
- Картинка предпросмотра.

Важно:
Это исходный проект, а не готовый APK. Сборка через GitHub Actions настроена, но ещё не запускалась.
Файл watchface.xml и совместимость с часами должны быть проверены после сборки/установки.
Дата, шаги, заряд, погода и фазы Луны пока не реализованы как живые данные.

Сборка в GitHub:
1. Загрузите содержимое этой папки в корень приватного репозитория GitHub (не загружайте ZIP как один файл).
2. Убедитесь, что workflow находится по пути .github/workflows/build.yml.
3. Откройте вкладку Actions и выберите Build watch face APK.
4. Нажмите Run workflow.
5. После успешной сборки скачайте артефакт Lange-Ultra-debug-apk — внутри будет app-debug.apk.

Проект использует Android Gradle Plugin 8.9.1, Gradle 8.11.1, JDK 17 и Android SDK 36.

Официальная документация:
https://developer.android.com/training/wearables/wff
https://developer.android.com/training/wearables/wff/setup
https://developer.android.com/training/wearables/wff/debug
