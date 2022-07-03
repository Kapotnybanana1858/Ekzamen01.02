<h1>Билет 13</h1>

![image](https://user-images.githubusercontent.com/40539112/177013623-da03ec3b-ba47-4de8-ad27-2aca21cc8b24.png)


<h2>Ответ на теоретический вопрос</h2>
<p>Во время тестирования существуют разные уровни. Уровни тестирования включают различные методологии, которые могут использоваться при проведении тестирования программного обеспечения. Основными уровнями тестирования программного обеспечения являются:</p>
<ul>
  <li>Функциональное тестирование
  <li>Нефункциональное тестирование
</ul>

<h4>Функциональное тестирование</h4>
<p>Это тип тестирования «черного ящика», основанного на спецификациях программного обеспечения, которое должно быть проверено. Приложение проверяется путем ввода ввода, а затем проверяется результат, который должен соответствовать функциям, для которых он предназначался. Функциональное тестирование программного обеспечения проводится в полной интегрированной системе для оценки соответствия системы указанным требованиям.</p>
<p>При тестировании приложения для работы есть пять шагов:</p>
<ol>
  <li>Определение функциональности, предназначенной для предполагаемого приложения.
  <li>Создание тестовых данных на основе спецификаций приложения.
  <li>Результат основан на тестовых данных и спецификациях приложения.
  <li>Написание тестовых сценариев и выполнение тестовых примеров.
  <li>Сравнение фактических и ожидаемых результатов на основе выполненных тестовых случаев.
</ol>
<p>Эффективная практика тестирования увидит вышеприведенные шаги, применяемые к политикам тестирования каждой организации, и, следовательно, она будет следить за тем, чтобы организация придерживалась самых строгих стандартов, когда речь идет о качестве программного обеспечения.</p>

<h4>Тестирование устройства</h4>
<p>Этот тип тестирования выполняется разработчиками до того, как установка будет передана группе тестирования для официального выполнения тестовых примеров. Модульное тестирование выполняется соответствующими разработчиками в отдельных единицах назначенных исходным кодом областях. Разработчики используют тестовые данные, отличные от тестовых данных команды по обеспечению качества.</p>
<p>Цель модульного тестирования состоит в том, чтобы изолировать каждую часть программы и показать, что отдельные части являются правильными с точки зрения требований и функциональности.</p>

<h4>Интеграционное тестирование</h4>
<p>Тестирование интеграции определяется как тестирование комбинированных частей приложения, чтобы определить, правильно ли они функционируют. Интеграционное тестирование может быть выполнено двумя способами: интеграционное тестирование снизу вверх и тестирование интеграции сверху вниз.</p>

<h4>Тестирование системы</h4>
<p>Тестирование системы тестирует систему в целом. После того как все компоненты интегрированы, приложение в целом проверяется строго, чтобы убедиться, что оно соответствует указанным стандартам качества. Этот тип тестирования выполняется специализированной группой тестирования.</p>

<h4>Регрессионное тестирование</h4>
<p>Всякий раз, когда делается изменение в программном приложении, вполне возможно, что это изменение повлияло на другие области приложения. Регрессионное тестирование выполняется для проверки того, что исправленная ошибка не привела к другой функциональности или нарушению бизнес-правил. Цель регрессионного тестирования состоит в том, чтобы гарантировать, что изменение, такое как исправление ошибки, не должно приводить к обнаружению другой неполадки в приложении.</p>

<h4>Приемочное тестирование</h4>
<p>Это, возможно, самый важный тип тестирования, так как он проводится командой по обеспечению качества, которая будет определять, соответствует ли приложение требуемым спецификациям и удовлетворяет требованиям клиента. Команда QA будет иметь набор предварительно написанных сценариев и тестовых примеров, которые будут использоваться для тестирования приложения.</p>
<p>Будет представлено больше идей о приложении, и на нем можно будет провести больше тестов, чтобы оценить его точность и причины, по которым был инициирован проект. Приемочные тесты предназначены не только для указания простых орфографических ошибок, косметологических ошибок или пробелов в интерфейсе, но и для указания на наличие ошибок в приложении, которые могут привести к сбоям системы или серьезным ошибкам в приложении.</p>
<p>Выполняя приемочные испытания в приложении, группа тестирования уменьшит, как приложение будет работать на производстве. Существуют также юридические и контрактные требования для принятия системы.</p>

<h4></h4>
<p></p>

<h4></h4>
<p></p>

<h2>Тестовые данные</h2>

<table>

<tr>
<th>Требование</th>
<th>Пароль</th>
<th>Результат</th>
</tr>


<tr>
<td>Количество символов от 8 до 20</td>
<td>qtgb&</td>
<td>False</td>
</tr>
 
<tr>
<td></td>
<td>hgtyU#84g</td>
<td>True</td>
</tr>

<tr>
<td></td>
<td>POGTREWWQasdfghjkl;$3gfd21</td>
<td>False</td>
</tr>

<tr>
<td>Наличие цифр</td>
<td>bgtvfrcde123#A</td>
<td>True</td>
</tr>

<tr>
<td></td>
<td>Zseqscawdx()</td>
<td>False</td>
</tr>

<tr>
<td>Наличие спецсимволов</td>
<td>Bg123!@#qazwsx</td>
<td>True</td>
</tr>

<tr>
<td></td>
<td>pkmlijlgtyh</td>
<td>False</td>
</tr>

<tr>
<td>Наличие прописных букв</td>
<td>GFD$#1frtgbn</td>
<td>True</td>
</tr>

<tr>
<td></td>
<td>tfcngrfyhb</td>
<td>False</td>
</tr>

<tr>
<td>Наличие строчных букв</td>
<td>#$3IjHyGbGf</td>
<td>True</td>
</tr>

<tr>
<td></td>
<td>TYUGHJBNM</td>
<td>False</td>
</tr>

</table>

<h2>Скриншот выполнения</h2>

![image](https://user-images.githubusercontent.com/40539112/177040134-61c6de57-f3cb-4008-a975-2748cbc7a998.png)
