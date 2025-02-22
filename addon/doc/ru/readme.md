# Магазин для NVDA
## Как использовать

Дополнение поставляется без назначенных горячих клавиш, и мы можем предоставить вам два ярлыка для этого, которые:

* Отображение окна со всеми дополнениями и информацией о них: нам будет показано окно со всеми дополнениями, которые есть в https:www.nvda.es
* Проверка наличие обновлений установленных дополнений: Магазин проанализирует дополнения, которые у нас есть, и те, для которых он найдёт обновления, предложит нам автоматически обновить их.

Мы можем назначить горячие клавиши для этих двух параметров, перейдя в меню NVDA / настройки / Жесты ввода / Магазин для NVDA.ES.

### Отображение окна со всеми дополнениями и информацией о них

На этом экране у нас будут все дополнения рядом с вкладкой и возможность перейти в ваш репозиторий и загрузить.

Если мы пройдем через окно, у нас будет список всех дополнений, поле только для чтения с выбранной вкладкой дополнения, кнопка "Загрузить плагин", кнопка "посетить веб-страницу", чтобы перейти на страницу дополнения, и кнопка "выйти".

Кроме того, у нас будет окно поиска, в котором вы можете написать то, что вы хотите найти, и если вы нажмете Enter, результаты будут отображаться в списке.

Чтобы вернуть весь список дополнений, вам просто нужно вернуться в поле поиска, удалить его содержимое и нажать Enter в пустом поле.

В поле вкладки, если дополнение имеет более одной ветви разработки, нам также будет показана информация.

Примечание переводчика: Поле вкладки - это область с детальной информацией о дополнении. Выбрав в списке дополнение, нажатием клавиши TAB переходим в поле вкладки.

Кнопка под названием "Загрузить дополнение" откроет меню с различными ветвями разработки дополнения, вам нужно будет выбрать одну для загрузки. В случае, если у вас есть только одна, вам будет предоставлен этот вариант.


На этом экране у нас есть следующие горячие клавиши для перемещения по интерфейсу:

* Alt + B: Перейти в окно поиска.
* Alt+L: Перейти к списку дополнений.
* Alt+I: Перейти в поле вкладки, чтобы просмотреть информацию о выбранном дополнении.
* Alt+D: Нажать кнопку "Загрузить дополнение".
* Alt + P: Перейти на Web-страницу дополнения.
* Alt+S, Escape, Alt+F4: Закрыть окно.

#### Контекстное меню в списке дополнений

В списке дополнений мы можем открыть контекстное меню либо с помощью клавиши Applications на клавиатуре, либо Shift + F10 для клавиатур, у которых нет клавиши Applications.

Такое меню состоит из двух подменю:

Фильтры и копировать в буфер обмена.

В подменю фильтры у нас есть следующие параметры:

* Показать все дополнения: этот параметр является предопределенным при первом запуске магазина дополнений.
Эта опция покажет нам все дополнения в базе данных.
Кроме того, этот параметр зависит от того, установлен ли флажок Сортировать дополнения магазина и поиск по алфавиту, поэтому, если этот флажок в параметрах установлен, список будет отсортирован по алфавиту, как и поиск в этом списке.
* Показать дополнения с поддержкой API 2021: этот параметр покажет нам только те дополнения, которые в манифесте отмечены такой совместимостью.
Кроме того, этот параметр зависит от того, установлен ли флажок Сортировать дополнения магазина и поиск по алфавиту, поэтому, если этот флажок в параметрах установлен, список будет отсортирован по алфавиту, как и поиск в этом списке.
Предупредить, что в этом списке будут пропущены те дополнения, в которых авторы в манифесте не указали правильную версию поддержки API и поставили поддержку ещё не вышедших API.
* Показать дополнения, отсортированные по автору: этот параметр покажет нам список дополнений, но отсортированный по имени автора.
* Показать по самым высоким и самым низким загрузкам: эта опция покажет нам все дополнения, но будет отсортирована по количеству загрузок дополнений.
Эти параметры выполняются индивидуально, не будучи кумулятивным их результатом.

Каждый вариант, когда мы его выбираем, меняет заголовок окна, чтобы сообщить нам, какой фильтр активен.

Параметры сохраняются в течение следующих нескольких раз, когда магазин активируется до перезапуска NVDA. После перезапуска настройки магазина возвращаются к своему первоначальному значению и список, загруженный в первый раз будет отображать все дополнения За исключением опции показать все дополнения, остальные параметры фильтруются только по первой ветвью разработки. Если дополнение имеет более одной ветви, они не будут учитываться, кроме основной ветви, для фильтрации результатов по каждому параметру.

В подменю копировать в буфер обмена у нас есть следующие параметры:

* Копировать информацию: если мы выберем этот параметр, вся вкладка выбранного дополнения будет скопирована в буфер обмена.
* Копировать ссылку на веб-страницу дополнения: если мы выберем эту опцию, ссылка на официальную страницу дополнения будет скопирована в буфер обмена.
* Копировать ссылку для загрузки дополнения: этот параметр, также  подменю, которое будет содержать ветви разработки дополнения "Stable" и "Dev". Когда мы выбираем один из пунктов, если их более одного, то ссылка копируется в буфер обмена.

Примечание переводчика: Такую ссылку на прямую загрузку дополнения, можно отправлять знакомым и друзьям по почте, в социальных сетях, вмессенджерах.

### Проверить наличие обновлений установленных дополнений

Это позволит нам обновить те дополнения, которые в каталоге  https://www.nvda.es будут новее, чем у нас в NVDA.

На этом экране вы можете выбрать, если есть обновления, те дополнения, которые вы хотите обновить.

Нам нужно будет отметить пробелом необходимые дополнения и нажать кнопку "Обновить".

На этом экране нам будет показано соответствующее обновление, если оно есть для выбранной ветви, перейдя в меню NVDA / Настройки / Параметры / магазин NVDA.ES,там мы можем выбрать, есть ли более одной ветви развития, которую мы хотим обновлять (это хорошо объяснено в следующем разделе)

На этом экране у нас есть следующие горячие клавиши:

* Alt+S: Отметить Все дополнения из списка, чтобы установить все обновления наших дополнений, установленные на нашем компьютере.
* Alt+D: Снять отметку со всех дополнений в списке, если они были ранее отмечены.
* Alt+A: Начать обновление тех дополнений, которые мы отметили в списке.
* Alt+C, Alt+F4 или Escape: Закрыть окно.

### Панель параметров

Вы сможете настроить некоторые аспекты магазина, перейдя в меню NVDA / Настройки / Параметры и найдя категорию "Магазин NVDA.ES".

* Включить или отключить автоматическую проверку обновлений.
Если мы установим этот флажок, появится поле со списком, в котором мы сможем выбрать, сколько времени пройдет между одной проверкой и другой.
Флажок" Включить или отключить проверку обновлений " отключен по умолчанию.
Поведение этой опции простое, магазин будет искать сервер, есть ли обновления в заданном временном диапазоне, и уведомлять нас системным уведомлением о том, сколько обновлений есть, и предложением открыть соответствующую опцию в магазине NVDA.ES для обновления.
Если эта опция включена, она будет искать 10 раз по диапазону заданного времени, а затем будет отключена. Это делается для того, чтобы не перегружать вызовами сервер.
Таким образом, если у нас установлен интервал 15 минут, - это 2часа 30 минут,  то через это время магазин перестанет проверять наличие обновлений.
В случае, если есть обновления, дополнение магазина будет производить проверку в 5 раз больше заданного временного диапазона, а затем отключится, каждый раз магазин будет сообщать нам, что обновления были найдены, пока мы не обновим.
* Сортировка в алфавитном порядке дополнений магазина и результатов поиска.
Если мы установим этот флажок, когда мы откроем магазин, нам будут показаны дополнения в алфавитном порядке. Кроме того, если мы ищем какие-либо дополнения, Результаты поиска будут отображаться в алфавитном порядке.
* Установка дополнений после загрузки.
Если мы установим этот флажок, после завершения загрузки дополнения, мастер установки  дополнений спросит нас, хотим ли мы установить дополнение.
* Установленные дополнения на сервере.
В этом списке нам будут показаны те дополнения, которые у нас установлены и, в свою очередь, находятся на сервере.
Будут отображаться только те, которые также поддерживают текущий API NVDA.
В этом списке мы можем выбрать, какую ветку обновления мы хотим для дополнения. Если мы нажмем пробел на любом дополнении, то развернем все ветви разработки для этого дополнения. Вы можете выбрать ту ветку, которую вы хотите по умолчанию, и выбор будет сохранен в списке.

Предупреждение: изменения в списке будут сохранены только в том случае, если вы нажмёте кнопку OK или Применить в диалоге параметров.
Этот список обновляется каждый раз, когда мы перезапускаем NVDA, добавляя, Если есть новые дополнения, или удаляя те, которых больше нет.

Поэтому, если мы удалим дополнение, а затем переустановим его, нам придется снова выбрать ветку, которую мы хотим.
Этот список как при первом создании, так и при каждом добавлении дополнения всегда будет по умолчанию ставить первую ветвь разработки на сервере.

Примечание переводчика: Первая ветвь разработки - это стабильная, если нет стабильной, то это будет разрабатываемая.
 
## Наблюдения

Когда вы будете проверять наличие обновлений, у вас будет две защиты:

1-й проверит, есть ли дополнения, которые будут удалены.

Если это так, эти дополнения исключаются, даже если есть обновления.

2º будет проверено, что дополнение на сервере соответствует требованиям API NVDA, которые мы установили.

Если проверка будет отрицательной, то дополнение не сможет быть установлено, даже если версия на сервере более новая, и сервер предлагает нам это дополнение.

При установке также были включены различные средства защиты:

1º теперь сообщит нам, если какие-либо дополнения не могут быть обновлены, и даст нам их названия.

2º на этом этапе также будет проверено, имеет ли дополнение для установки минимальную версию для использования на установленном NVDA.

3º Магазин NVDA.Es не позволит продолжать проверять наличие обновлений, если мы уже сделали обновление одного или нескольких дополнений и не решили перезапустить NVDA для сохранения изменений.

4º если у нас включена опция "проверить наличие обновлений установленных дополнений" каждый раз, когда вы ищете и обнаруживаете, что мы не перезапустили NVDA, мы будем уведомлены системным уведомлением.

5-й точно так же, если мы попытаемся включить опцию под названием “проверить наличие обновлений установленных дополнений" и не перезапустили NVDA, скринридер будет показывать сообщение о том, что мы должны перезапустить NVDA, чтобы применить изменения.

6º в худшем случае, если библиотека магазина не позволит загружать, потому что у нас нет интернета, нам будут показаны информационные сообщения в диалоге NVDA, а также, если мы попытаемся получить доступ к магазину, мы будем предупреждены речевым сообщением.

Это улучшило функцию, которая проверяет наличие обновлений, теперь намного надежнее, а также добавляет, в свою очередь, вышеупомянутые защиты.

Было сделано много внутренних улучшений, чтобы сделать его более надежным.

Этот магазин дополнени йнаходится в стадии тестирования, поэтому мы просим Вас понять, что могут быть ошибки.

Мы благодарим Вас за то, что вы связались, чтобы сообщить нам о них и чтобы мы исправили их как можно скорее.

Наслаждайтесь магазином для NVDA!
 