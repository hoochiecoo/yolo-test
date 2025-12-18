# Flutter YOLO Example CI/CD

Этот проект был сгенерирован автоматически для сборки APK через GitHub Actions.

## Как использовать

1. Запушьте этот код в репозиторий GitHub.
2. Перейдите во вкладку "Actions".
3. Дождитесь завершения workflow "Build Flutter APK".
4. Скачайте артефакт (app-release.apk).

## Заметки
Файл `camera_inference_screen.dart` является базовой заглушкой. Для реальной работы YOLO вам необходимо добавить логику ObjectDetector из пакета ultralytics_yolo и поместить файл модели (.tflite) в папку `assets/models/`.
