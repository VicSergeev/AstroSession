# AstroSession
apple script for automation of you astronomical sessions

## Description (English)
This AppleScript automates the organization of astrophotography sessions by managing captured images, logging session details, and structuring data efficiently. It is designed for use with Canon EOS Utility or similar programs that save photos to a specific folder. Will be helpfull for Electronically Assisted Astronomy sessions.

### Features:
- Automatically creates a new session folder with the current date.
- Allows users to input camera and optics details.
- Organizes images into folders named after observed objects.
- Logs metadata such as image capture time, camera, and optics used.
- Provides options to change camera and optics settings during the session.
- Saves session and object logs to text files.

### Workflow:
1. The script prompts the user for camera and optics details.
2. It continuously asks for an object name (or a command like `stop` to end the session or `change` to update settings).
3. Photos are moved into folders named after objects.
4. Logs are created for each observed object and the overall session.
5. At the end of the session, all logs are saved, and the user is notified.

---

## Описание (Русский)
Этот AppleScript автоматизирует организацию астрофотографических сессий, управляя сохранёнными изображениями, ведя журнал сессии и структурируя данные.

### Возможности:
- Автоматически создаёт новую папку для сессии с текущей датой.
- Позволяет пользователю вводить данные о камере и оптике.
- Организует фотографии в папки с названиями наблюдаемых объектов.
- Логирует метаданные, такие как время съёмки, камера и оптика.
- Позволяет изменять настройки камеры и оптики в процессе сессии.
- Сохраняет журналы сессии и объектов в текстовые файлы.

### Процесс работы:
1. Скрипт запрашивает у пользователя название камеры и оптики.
2. В цикле запрашивает название объекта (или команду `стоп` для завершения либо `изменить` для изменения настроек).
3. Фотографии перемещаются в папки, названные в честь объектов.
4. Создаются логи для каждого объекта и общей сессии.
5. В конце сессии все логи сохраняются, и пользователь получает уведомление.
