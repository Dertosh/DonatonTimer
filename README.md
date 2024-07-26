# Донатон Таймер

**Донатон Таймер** — это приложение для управления таймером, которое интегрируется с донатами DonationAlerts, позволяя отслеживать и управлять временем в зависимости от поступивших донатов. 

## 🎯 Ключевые возможности

- ### Интерфейс программы под Windows

  ![Интерфейс](https://github.com/MjKey/DonatonTimer/blob/main/img/main.jpg?raw=true)

  - Есть тёмная тема
  - Удобное управление
  - Пепежка

- **Веб-интерфейс для управления таймером:**
  - Старт/Стоп таймера
  - Изменение времени на таймере

- **Управление таймером с телефона:**
  - Доступ к веб-интерфейсу с мобильных устройств
  - Удобное управление таймером в мобильной версии

- **Интеграция с донатами:**
  - Отображение последних донатов
  - Отображение топ донатеров
  - Автоматичкое прибавление времени от доната
  - Настройка - сколько минут прибавить за 100 рублей.

- **Мини-версия для Док-Панели OBS:**
  - Упрощённый интерфейс для использования в док-панели OBS
 
## 🛠️ Установка и запуск

### Установка

1. **Скачайте установочный файл:**
   - Перейдите в раздел [Releases](https://github.com/MjKey/DonatonTimer/releases) и скачайте последнюю версию `DTimer Setup.exe`.

2. **Запустите установочный файл:**
   - Дважды щелкните по скачанному файлу `DTimer Setup.exe` и следуйте инструкциям на экране для установки приложения.

## 🚀 Использование

- **Интерфейс и другое:**
  - `http://localhost:8080/timer` для вставки в источник "Бразуер" - таймер собствнно будет отображаться в OBS.
  - Перейдите на `http://localhost:8080/dashboard` для веб-панели управления в бразуере.
  - `http://localhost:8080/mini` для встравивание в док-панель* OBS.
 
  *Для этого в OBS Studio -> Док-панели (D) -> Пользовательские док-панели браузера (C)
  ![Настройка док-панели](https://github.com/MjKey/DonatonTimer/blob/main/img/dockpanel.jpg?raw=true)

## 💬 Вопросы и поддержка

Если у вас есть вопросы или вы столкнулись с проблемами, не стесняйтесь открыть issue на [GitHub](https://github.com/MjKey/DonatonTimer/issues).

## 📝 Лицензия

Этот проект лицензируется под лицензией MIT — см. [LICENSE](LICENSE) для подробностей.

---

### Сборка из исходного кода

1. **Клонируйте репозиторий:**

   ```bash
   git clone https://github.com/MjKey/DonatonTimer.git
   ```

2. **Перейдите в директорию проекта:**

   ```bash
   cd DonatonTimer
   ```

3. **Установите зависимости:**

   ```bash
   flutter pub get
   ```

4. **Соберите проект для Windows:**

   ```bash
   flutter build windows
   ```
   
   **Или запустите для Windows**

   ```bash
   flutter run -d windows
   ```
