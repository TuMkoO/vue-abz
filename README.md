# vue-abz

https://tumkoo.github.io/vue-abz/
<br><br>
<h1>Тестовое задание 2020</h1>
<h2>Технические требования</h2>
<ul>
    <li>React / Vue / Angular ( version 6+);</li>
    <li>HTML5 / CSS3;</li>
    <li>CSS препроцессор (Sass/Less) или PostCSS;</li>
    <li>Разметка должна быть pixel-perfect (desktop: последняя версия Chrome / FF / Safari / Edge,
      mobile/tablet: последняя версия Safari на iOS 12+ и Chrome на Android 7+);</li>
    <li>Минимальная ширина экрана 360px;</li>
    <li>Максимальная ширина экрана 2560px;</li>
    <li>Максимальная ширина основного контейнера 1170px;</li>
    <li>Разметка должна быть готова к переполнению содержимого, включая длину заголовка блока. Если текст длиннее чем может отображать блок - Вы должны его обрезать и показать знак «...» с
      помощью CSS или Javascript.</li>
</ul>
<h2>Задание</h2>
<p>1. Вам необходимо реализовать responsive верстку HTML5/CSS3 в соответствии с макетами
(mockups) http://view.maquetter.com/rkymlp/0201 - 0205 и стайл гайд (style guide)
http://view.maquetter.com/rkymlp/0101 . Все необходимые исходники Вы сможете найти тут .</p>
<p>2. Все CTA (call to action) ссылки/кнопки должны вести на регистрацию. Обращаю Ваше внимание
на тот факт, что хэдер должен быть закреплен вверху страницы при скролле. Также обратите
внимание что:
<ul>
  <li>Все изображения на сайте должны поддерживать Retina экраны (для моб версии).</li>
  <li>Используйте CSS препроцессор (Sass/Less) или PostCSS.</li>
  <li>Организуйте Ваши CSS стили в читаемом виде (группируйте CSS по функциональности,
      пишите разъясняющие комментарии, разделяйте стили на несколько файлов по
      функциональности и т.д.).</li>
</ul> </p>
<p>3. Работа с REST API (GET). Тут Вы найдете API документацию .
<ul>
  <li>Используя полученные данные юзеров реализуйте вывод блока “Our cheerful users” в
    соответствии с макетом. Кнопка “Show more” должна подгружать пользователей из API
    согласно макетам. Кнопка “Show more” должна быть скрыта, когда больше нет
    пользователей в БД (достигнута последняя страница результатов в API). Пользователи
    отсортированы по дате регистрации (новые первые).</li>
  <li>Обратите внимание на mockups и style guide при работе с блоком юзеров. Задание
    предполагает ваше внимание к деталями вывода контента. Такие детали как количество
    блоков, “...”, tooltips, перенос строк и т.п.</li>
  <li>Для отображения радиобаттонов на форме регистрации используйте GET /positions
    метод из API документации.</li>
</ul>
</p>
<p>4. Работа с REST API (POST) – форма регистрации
<ul>
  <li>Реализовать валидацию на фронт-енд части в соответствии с макетами и API
    документацией.</li>
  <li>Реализовать бизнес логику формы регистрации в соответствии с макетами и API
    документацией.</li>
  <li>После успешной регистрации обновить список пользователей в блоке “Our cheerful
    users”. Если кнопка “Show more” была нажата (т.е. больше чем одна страница
    пользователей была загружена из API), то свернуть все и отобразить только первых 6
    пользователей. В результате новый пользователь будет выведен первым и Вы сможете
    проверить корректность работы пункта 5b без перезагрузки страницы.
    Важно! Каждую ночь список пользователей будет автоматически сброшен (на начальные 45
    пользователей).</li>
</ul> 
</p>
