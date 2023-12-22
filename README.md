# goit-markup-hw-01

  <!-- також можно включити форматування через ctrl+shift+p -> format document -> prettier -->
  <!-- to navigae fast between recent folders/workspaces just click shortcut ctrl+/ -->

<!-- <a href="">Логотип сайту компанії</a> код для логотипу, він буде як текст -->
<!-- mdn and css.in.ua to check html tegs -->

<!-- font-weight - for example 500 (medium), 400 (normal), 700 (bold)  - -->
<!-- font-style normal, italic, oblique, initial, inherit  | -->
<!-- text-transform: none | uppercase | lowercase | capitalize -->
<!-- text-align: left | right | center | justify -->
<!-- line-height - міжрядковий інтервал -->
<!-- letter-spacing інтервал між символами -->
<!-- text-decoration: none | underline | line-through | overline -->
<!-- list-style-type: none; to remove bullets in ul in css -->

# goit-markup-hw-03

1. box-sizing: content-box border-box inherit
2. box-sizing: border-box
3. глобальний бордер бокс: _, _::before, \*::after { box-sizing: border-box; }

/_ Решта коду _/ (не треба коли подклбчен нормалайз)

4. якщо підключений нормалізатор то скидати маржини для боді не треба
5. border: width style (solid, dashed, dotted) color
6. border-radius: px or %
7. can pick for ex border-top-right-radius or border-bottom-left-radius..
8. overflow: hidden щоб кути фото не виходили за кордони рамки (не були видимі)
9. overflow: visible hidden scroll auto
10. default for overflow is visible
11. display: block/ inline/ flex(block) or inline-flex/ inline-block/ none
    (allow to hide element)
12. margin collapse- only for blocks, always chooses bigger margin among two
13. щоб фото підлаштовувалась під ширину батьківського елементу треба поставити
    max-width: 100%
14. object-fit: fill/ contain/ cover/ scale-down/ none
15. flex-direction: row/ row-reverse/ column/ column-reverse
16. justify-content: flex-start/ flex-end/ center/ space-between/ space-around/
    space-evenly (for main axis)
17. align-items: strach/ flex-start/ flex-end/ center/ baseline (for cross axis,
    analogue for justify-content)
18. flex-wrap: nowrap (default)/ wrap/ wrap-reverse
19. .item {width: calc((100% - 20px)/3)} 100% - кількість*проміжків*у*рядку \*
    значення*одного*проміжку) / кількість*елементів*у*рядку
20. align-content(for multiple rows) flex-start/ flex-end/ center/
    space-between/ space-around/ space-evenly/ stretch
21. flex-basis (instead of width for flexbox)
22. min-width or max-width are limits for elements
23. flex-grow (more space, default 0) or flex-shrink (less space, default 1)
24. min-height: 100vh (100%)
25. align-self: auto/ flex-start/ flex-end/ center/ baseline/ stretch
26. order: позиція
27. Псевдокласи :first-child і :last-child
28. :not()
29. nth-child(2n+1) or nth-child(odd)
30. nth-child(2n) or nth-child(even)
