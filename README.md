# postmortem
Неплохой пример: https://status.cloud.yandex.ru/incidents/8

# Summary

*Кратко о том, что происходило и почему. Это краткое и информативное описание аварии, оно должно быть понятно любому человеку без контекста.*

# Root cause

# Ущерб (impact)

**Качественная оценка**
*Какой сервис (какие сервисы) были затронуты, какой функционал не работал, как долго это продолжалось. Была ли потеря или порча данных.*

**Количественная оценка**
*По метрикам приложения и приложений-клиентов (сколько запросов отпало, насколько выросла latency и т.п.).*

# Графики

*Ссылки на снэпшоты графиков из графаны: системные метрики машин, дашборды пострадавших сервисов. Подпиши, куда какая ссылка ведет.*

# Как заметили

*Как узнали о проблеме. По каким алертам, что написали в саппорт, etc. *

# Кто был уведомлен, когда и как

# Триггер

*Развернуто опиши, что послужило триггером факапа: релиз (какой, когда), повышение нагрузки (от какого сервиса, пользовательского сценария и т.п.), проблема с железом (где находится, за что отвечает). *

# Причины

*Подробно опиши и проанализируй причины произошедшего. Опиши механизм падения. Причинно-следственные связи должны быть понятны человеку без контекста.*

*Не нужно писать от первого лица, оправдываться или винить своих коллег. Если в причинах фигурирует человеческий фактор, нужно докопаться, какой именно информации не хватило: осведомленности о процессах в команде, о механике работы системы, логике интеграции.*

# Что предприняли

*Что сделали непосредственно для решения проблемы и почему: "перезапустили сервис", "откатили релиз", "дважды перезагрузили машины", "сидели и наблюдали, рассосалось само", etc.*

# Хронология

*Опиши все значимые моменты в происшествии: когда внесли ломающее изменение, когда выстрелили алерты, шаги по тушению пожара, etc. Все метки времени укажи с датой.*

# Выводы

**Что пошло как надо**
*Какие механизмы помогли в обнаружении, предотвращении и тушении факапа.*

**Что пошло не так**
*Какой автоматики не хватило, чтобы факапа не произошло. Можно ли предотвратить подобное в будущем. Что уменьшило бы время реакции, длительность факапа, ущерб.*

**Где повезло**
*Моменты, которые по случайности предотвратили больший ущерб. Случайно посмотрели на метрики сервиса, заметили подозрительную строчку в логах, раскапывая другую проблему, нужный человек оказался у компьютера в нерабочее время.*

# Задачи

*Ссылки на задачи в трекере, которые помогут уменьшить ущерб, ускорить реакцию, убрать случайности, избежать подобного факапа в будущем. Не ставь абстрактные или невыполнимые задачи ("писать код лучше", "исправить все баги в коде"). Этот постмортем должен зависеть от задач через отношение depends on.*
