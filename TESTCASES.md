
 Тест-кейсы для счётчиков экологического вклада

### Визуальные тесты

**TC-01: Соответствие эталонному дизайну**  
**Цель:** Удостовериться, что UI счётчиков полностью соответствует предоставленному дизайн-макету.
1. Выполнить pixel-perfect сравнение с эталонным дизайном.
2. Подтвердить идентичность цветов, шрифтов, иконок и расположения элементов.
3. Документировать любые расхождения.

**TC-02: Корректность отображения иконок**  
**Цель:** Проверить отображение иконок на предмет искажений или ошибок.
1. Подтвердить, что иконки чёткие и без пикселизации.
2. Убедиться в тематическом соответствии иконок функциям счётчиков.

**TC-03: Читаемость шрифтов**  
**Цель:** Оценить читаемость текста на всех счётчиках.
1. Проверить разборчивость текста на разных устройствах.
2. Удостовериться в соответствии стиля шрифтов стандартам бренда.

### Функциональные тесты

**TC-04: Верность подстановки единиц измерения**  
**Цель:** Убедиться, что микрофронтенд корректно обрабатывает подстановку единиц измерений.
1. Провести тестирование конвертации единиц (например, 1000 л = 1 м³).
2. Зафиксировать правильность отображения изменённых значений.

**TC-05: Актуальность данных с бэкенда**  
**Цель:** Подтвердить, что счётчики обновляются в реальном времени при изменении данных на бэкенде.
1. Симулировать изменение данных на сервере.
2. Проверить отзывчивость и обновление счётчиков.

**TC-06: Интерактивность элементов UI**  
**Цель:** Исследовать реакцию UI на взаимодействие пользователя.
1. Проверить эффекты при наведении курсора на элементы.
2. Оценить визуальную обратную связь.

### Дополнительные тесты

**TC-07: Адаптивность дизайна**  
**Цель:** Проверить адаптивность интерфейса при изменении размеров окна браузера.
1. Изменять размеры окна и анализировать поведение элементов.
2. Подтвердить корректное отображение на стандартных разрешениях экранов.

**TC-08: Локализация интерфейса**  
**Цель:** Удостовериться в правильности отображения текста на счётчиках при смене языка интерфейса.
1. Провести смену языка через настройки интерфейса.
2. Проверить безошибочность и правильность локализации текста на счётчиках.

**TC-09: Реагирование на негативные значения**  
**Цель:** Проверить, как интерфейс обрабатывает отрицательные значения счётчиков.
1. Подать на вход отрицательные значения и проверить реакцию интерфейса.
2. Убедиться, что интерфейс отображает сообщение об ошибке или корректно обрабатывает отрицательные значения.

**TC-10: Тестирование кнопки сброса счётчиков**  
**Цель:** Проверить функциональность кнопки сброса счётчиков.
1. Нажать на кнопку сброса и убедиться, что все счётчики сбрасываются к исходным значениям.
2. Проверить, что после сброса счётчики корректно обновляются при изменении данных на бэкенде.

**TC-11: Проверка поддержки кэширования**  
**Цель:** Убедиться, что интерфейс корректно работает с кэшированием данных.
1. Провести тестирование на наличие и отсутствие кэшированных данных при открытии страницы.
2. Проверить, что интерфейс корректно обновляет данные при обновлении страницы или очистке кэша.

**TC-12: Проверка влияния на производительность страницы**  
**Цель:** Оценить влияние счётчиков на производительность страницы.
1. Измерить время загрузки страницы с счётчиками и без них.
2. Убедиться, что добавление счётчиков не значительно увеличивает время загрузки и производительность страницы не ухудшается.