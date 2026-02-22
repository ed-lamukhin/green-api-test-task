# green-api-test-task
# Тестовое задание GREEN-API (DevOps)

В этом репозитории находится простая HTML-страница для работы с методами GREEN-API и отображения ответов API на странице.

## Реализованные методы
- `getSettings`
- `getStateInstance`
- `sendMessage`
- `sendFileByUrl`

## Как запустить

### Вариант 1: Локально
1. Скачайте файл `index.html`
2. Откройте его в любом современном браузере (Chrome / Edge / Firefox)

### Вариант 2: Через GitHub Pages
Та же страница опубликована через GitHub Pages по ссылке ниже.

## Как пользоваться
1. Зайдите в личный кабинет GREEN-API и создайте новый инстанс (бесплатный аккаунт разработчика).
2. Отсканируйте QR-код и подключите ваш номер телефона к инстансу.
3. Откройте страницу и введите:
   - `idInstance`
   - `ApiTokenInstance`
4. Нажимайте кнопки по порядку:
   - `getSettings`
   - `getStateInstance`
   - `sendMessage`
   - `sendFileByUrl`

### Автоподстановка номера телефона
После нажатия `getSettings` страница извлекает поле `wid` из ответа API (например, `77770285725@c.us`) и автоматически подставляет номер телефона в поля для отправки сообщения и файла.

## Примечания
- Номер телефона нужно вводить **без знака `+`** (только цифры).
  Он автоматически преобразуется в формат WhatsApp `chatId`: `<номер>@c.us`
- Все ответы API отображаются в правой части страницы в поле **только для чтения (read-only)**.

## Ссылки
- Репозиторий GitHub: https://github.com/ed-lamukhin/green-api-test-task
- Опубликованная страница (GitHub Pages): https://ed-lamukhin.github.io/green-api-test-task/  
- Ссылка для скачивания https://raw.githubusercontent.com/ed-lamukhin/green-api-test-task/main/Test_Task_DevOps.pdf
