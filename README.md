Налаштуй GitHub Pages і додай посилання на живу сторінку в шапку GitHub-репозиторія.

«A6» Скрипт модального вікна підключений в HTML окремим файлом modal.js.

Оформлення
«C1» Для всіх ефектів ховер і фокуса (колір, фон, тінь) зроблені переходи. Час - 250ms, функція розподілу часу - cubic-bezier(0.4, 0, 0.2, 1).

«C2» У переходах та анімаціях явно зазначені анімовані властивості. Ніде немає значення all.

«C6» Синій оверлей в картках сторінки Портфоліо виїжджає знизу, як показано на відео.

card overlay preview
«C7» У псевдоелементів відсутній текстовий контент у властивості content. Вони використані виключно для декоративного оформлення.

Модальне вікно
«D1» Виконана розмітка і оформлення «бекдропа» (темного напівпрозорого фону) модального вікна.

«D2» «Бекдроп» заповнює 100% висоти і ширини в'юпорту браузера і фіксований в ньому.

«D3» Виконана розмітка і оформлення модального вікна.

«D4» Модальне вікно вертикально і горизонтально спозиційоване посередині бекдропа.

«D5» Виконана розмітка і оформлення кнопки закриття модального вікна у верхньому правому куті.

«D6» Спочатку модальне вікно і бекдроп приховані за допомогою класу is-hidden на бекдропі, в селекторі якого використовуються властивості visibility, opacity і pointer-events.

«D7» Якщо прибрати з бекдропа клас is-hidden - з'являється бекдроп і модальне вікно.

«D8» Поява і приховування модального вікна анімовано за допомогою переходу з довільним ефектом, наприклад scale або translate, і opacity.

/_ --help-- _/
/_ p,
h1,
h2,
h3,
.page-nav-list,
.logo,
.contacts,
.footer-address {
outline: 2px solid tomato;
}
li {
outline: 2px solid blueviolet;
}
.coteiner {
outline: 2px solid teal;
}
.section {
outline: 2px solid green;
} _/

/_ .portfolio-filter li + li {
margin-left: 8px;
} _/
/_ .portfolio-filter + .portfolio-galery {
margin-top: 50;
} _/

/_ .benefits-list .icon {
width: 70px;
height: 70px;
} _/

/_ .btn-secondary {
background-color: var(--color-bg-secondary);
color: var(--color-nav-and-title);
}
.btn-primary {
background-color: var(--color-accent);
color: var(--color-text-theme-dark);
} _/

/_ .portfolio-galery-link:hover,
.portfolio-galery-link:focus{
outline: 5px solid teal;
box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06),
1px 4px 6px rgba(0, 0, 0, 0.16);
} _/
