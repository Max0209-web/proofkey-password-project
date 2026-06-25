Индивидуальный проект: Создание надежных паролей

Автор: Васильев Максим Дмитриевич
Колледж: ИТ.Москва
Группа: 1И-6-25

Состав сайта:
- index.html - структура страницы;
- styles.css - стили и адаптивная верстка;
- app.js - генератор паролей и оценка стойкости;
- assets/password-visual.png - визуальный материал для первого экрана.

Особенности:
- генерация выполняется через crypto.getRandomValues;
- пароль не отправляется на сервер;
- есть режим случайного пароля и режим пасфразы;
- оценка стойкости учитывает длину, набор символов, энтропию и слабые шаблоны.

Источники:
- NIST SP 800-63B: https://pages.nist.gov/800-63-4/sp800-63b.html
- NCSC Three random words: https://www.ncsc.gov.uk/collection/top-tips-for-staying-secure-online/three-random-words
- NCSC Managing your passwords: https://www.ncsc.gov.uk/collection/top-tips-for-staying-secure-online/password-managers
