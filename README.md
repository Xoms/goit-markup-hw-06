# goit-markup-hw-06

## Домашнее задание
- Создай репозиторий goit-markup-hw-06.
- Склонируй новый репозиторий и перенеси в него файлы предыдущей работы.
- Добавь разметку и оформление модального окна с формой заявки.
- Добавь разметку и оформление формы подписки на рассылку в футере.
- Для всех переходов используй следующие значения: время - 250ms, функция распределения времени - cubic-bezier(0.4, 0, 0.2, 1).
- Настрой раздачу статики с GitHub Pages и добавь ссылку на живую страницу в шапку GitHub-репозитория.

## Дополнительные критерии
- Создан репозиторий goit-markup-hw-06.
- У всех инпутов в формах прописан атрибут name.
- У инпутов, где необходимо, есть связанный элемент <label>.

### Форма подписки на рассылку
- Создана разметка и набраны стили формы подписки на рассылку в футере.

### Модальное окно
- Есть разметка и оформление модального окна и его бекдропа (тёмного полупрозрачного фона).
- Изначально модальное окно скрыто при помощи класса is-hidden (свойства visibility, opacity и pointer-events). Если класс убрать - модалка появляется.
- Появление и скрытие модального окна анимированы при помощи перехода с произвольным эффектом, например scale или translate, и opacity.

### Форма в модальном окне
- В модальном окне есть разметка формы заявки.
- Выполнена разметка и оформление всех иконок в полях формы.
- Текст в полях формы (имя, телефон, почта и комментарий) это не palceholder, а текст в теге <label>, спозиционированный поверх инпута.
- При получении полем фокуса - текст метки анимированно уезжает наверх (как показано на макете активного состояния элементов формы).
- Оригинальный чекбокс о принятии лицензионного соглашения в форме заявки скрыт, а его визуальное оформление сделано вручную, при помощи псевдоэлемента и векторного изображения галочки.
- Когда инпут получает фокус, иконка в нём меняет цвет на основной цвет акцента.

### Открытие модального окна (не обязательно)
- Модальное окно с формой заявки открывается по клику на кнопку "Заказать услугу" в секции Hero. 

Для того чтобы скрипт сработал необходимо добавить в разметку специальные атрибуты, по которым скрипт ищет элементы:

- data-modal-open - на кнопку открытия модального окна
- data-modal-close - на кнопку закрытия модального окна
- data-modal - на бекдроп модального окна