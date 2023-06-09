HelpDesk: Frontend

![CI](https://github.com/nikulin68/HelpDesk-Frontend/actions/workflows/web.yml/badge.svg)

Легенда

Часть API вами написано, пора приступить к своим прямым обязанностям - написанию фронтенда, который будет с этим API работать.

Описание

Общий вид списка тикетов (должны загружаться с сервера в формате JSON):



Модальное окно добавления нового тикета (вызывается по кнопке "Добавить тикет" в правом верхнем углу):



Модальное окно редактирования существующего тикета (вызвается по кнопке с иконкой "✎" - карандашик):



Модальное окно подтверждения удаления (вызывается по кнопке с иконкой "x" - крестик):



Для просмотра деталей тикета нужно нажать на тело тикета (но не на кнопки - "сделано", "редактировать" или "удалить"):



Ваше приложение должно реализовывать следующий функционал:

Отображение всех тикетов
Создание нового тикета
Удаление тикета
Изменение тикета
Получение подробного описание тикета
Отметка о выполнении каждого тикета
Весь этот функционал должен быть связан с сервером через методы. Например для удаления нужно отправить запрос с соответствующим методом, получить подтверждение и подтянуть обновлённый список тасков.

В качестве бонуса можете отображать какую-нибудь иконку загрузки (см. https://loading.io) на время подгрузки.

Авто-тесты к данной задаче не требуются. Все данные и изменения должны браться/сохраняться на сервере, который вы написали в предыдущей задаче.

В качестве результата пришлите проверяющему ссылку на GitHub репозиторий.

Заметка
P.S. Подгрузка подробного описания специально организована в виде отдельного запроса, мы прекрасно понимаем, что на малых объёмах информации нет смысла делать её отдельно.

[![Build status](https://ci.appveyor.com/api/projects/status/c1gw2fwdjl0k7fv6/branch/main?svg=true)](https://ci.appveyor.com/project/nikulin68/helpdesk-frontend/branch/main)
