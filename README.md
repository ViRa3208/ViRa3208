<!DOCTYPE html>
<html lang="ru">
<head>
<tittle> Лабораторная №1 </tittle> <br>
</head>
<body bgcolor='white' text='black'>
<ol>
<li><a href="https://ria.ru/">  абсолютная гиперссылкана главную страницу сайта</a></li>
<li><a href="https://ria.ru/"> абсолютная  на главную сайта в протоколе https </a>
<li><a href="ftp://laba.com/text.zip">  ссылка на файл на сервере FTP без авторизации</a>
<li><a href="ftp://lg:pr@laba.com/text.zip"> ссылка на файл на сервере FTP c авторизацией </a>
<li><a href="https://ru.wikipedia.org/wiki/%D0%92%D0%BE%D0%B5%D0%BD%D0%BD%D1%8B%D0%B9_%D0%BA%D0%BE%D0%BD%D1%84%D0%BB%D0%B8%D0%BA%D1%82"> ссылка на фрагмент страницы некоторого сайта </a>
<li><a href="#top"> ссылка на фрагмент текущей страницы</a></li>
<li> <a href="https://www.yandex.ru/search?a=youtube&b=youtube">ссылка с двумя параметрами в URL</a> </li>
<li>Навигация по странице сайта
<ul>
<li><a href="https://ria.ru/" title="Заглавная страница">Заглавная страница</a></li>
<li><a href="https://ria.ru/world/" title="В мире">В мире</a></li>
<li><a href="https://ria.ru/economy/" title="Экономика">Экономика</a></li>
<li><a href="https://ria.ru/society/" title="Форум">Форум</a></li>
<li><a href="https://ria.ru/incidents/" title="Проишествия">Проишествия</a></li>
<li><a href="https://ria.ru/defense_safety/" title="Армия">Армия</a></li>
<li><a href="https://ria.ru/science/" title="Наука">Наука</a></li>
<li><a href="https://ria.ru/culture/" title="Культура">Культура</a></li>
<li><a href="https://rsport.ria.ru/" title="Спорт">Спорт</a></li>
</ul>
</li>
<li><a href="https://www.pinterest.ru/" rel="nofollow"> ссылка по которой запрещен переход поисковикам</a>
<li> <noindex><a href="https://www.pinterest.ru/" rel="nofollow">Ссылка запрещенная для индексации поисковиками</a></noindex> </li>
<li><a title="href отсутствует">Ссылка без href</a></li>
<li><a href="" title="Пустой href">Ссылка с пустым href</a></li>
<li><a href="https://i.pinimg.com/564x/5f/60/37/5f6037ac66542b588c4f76abe5c0f62f.jpg"><img src="https://i.pinimg.com/564x/3a/0d/18/3a0d18e15da7f6fd58131e89c41ff9b7.jpg" alt="" title="ссылка-изображение"></a></li>
<li><img src="https://i.pinimg.com/564x/dd/72/62/dd726201a3fe0d0a986e091fec43c4c8.jpg" usemap="#footbol">
<map name="footbol">
<area shape="rect" coords="118, 246, 113, 267" href="https://ru.wikipedia.org/wiki/%D0%A4%D1%83%D1%82%D0%B1%D0%BE%D0%BB">
<area shape="circle" coords="113, 130, 160" href="https://ru.wikipedia.org/wiki/%D0%A4%D1%83%D1%82%D0%B1%D0%BE%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5_%D0%B2%D0%BE%D1%80%D0%BE%D1%82%D0%B0">
</map></li>
<li><p>  Прохоровская трагедия советских  <a href="https://topwar.ru/144253-prohorovskaya-tragediya-sovetskih-tankistov.html">танкистов </p></li>
<li><a href="https://htmlacademy.ru/blog/frontend/html/index.html">в текущем каталоге</a></li>
<li><a href=".../about/text.html">в каталоге about</a></li>
<li><a href=".../text.html">в каталоге на 1 уровень выше</a></li>
<li><a href=".../.../example.html">на 2 уровня выше</a></li>
<li><a href="/"> Сокращенная ссылка на главную </a></li>
<li><a href=".../input">Сокращенная ссылка на внутреннюю </a></li>
<ol>
<hr>
<form action="#" method="post">
<label>
Имя:<br />
<input type="text" name="username" value="">
</label><br />
<label>
E-mail:<br />
<input type="email" name="email" value="">
</label><br />
<label>
Дата рождения:<br />
<input type="date" name="birthday" value=""></label><br/>
<form action="#" method="post">


Пол:<br />
<label><input type="radio" checked="checked"
name="radio-group-1" value="Значение1" />
женский</label>
<label><input type="radio"
name="radio-group-1" value="Значение2" />
мужской</label><br /></form>

Количество конечностей:<br />
<label><input type="radio" checked="checked"
name="radio-group-1" value="Значение1" />
0</label>
<label><input type="radio"
name="radio-group-1" value="Значение2" />
1</label>
<label><input type="radio"
name="radio-group-1" value="Значение2" />
2</label>
<label><input type="radio"
name="radio-group-1" value="Значение2" />
3</label>
<label><input type="radio"
name="radio-group-1" value="Значение2" />
4</label>
<label><input type="radio"
name="radio-group-1" value="Значение2" />
5</label><br />

<label>
Сверхспособности:<br />
<select name="field-name-3">
<option value="Значение1" selected="selected">Бессмертие</option>
<option value="Значение2">Прохождение сквозь стены</option>
<option value="Значение3">Левитация</option>
</select>
</label><br />


<label>
Биография:<br />
<textarea name="field-name-2"></textarea>
</label><br />

Чекбокс:<br />
<label><input type="checkbox" checked="checked"
name="check-1" />с контрактом ознакомлен (а)</label><br />

Кнопка отправки формы
<input type="submit" value="Отправить" />
</form>
</html>
