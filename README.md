![image](https://github.com/user-attachments/assets/7b996948-07ec-4e42-acea-ef8a8a6bc9db)

   Prometheus как обработчик метрик собирает информацию с экспортеров(которые могут собираться как через протоколы (например SNMP),так и через отдельные самостоятельные экспортеры,которые ставятся там,где нужно организовать сбор метрик(например сервер Linux))

   После сбора метрик prometheus может использовать Alermanager,который в свою очередь конечной инстанцией может использовать сервис для уведомлений(например telegram, email)

   Так же для графического представления метрик в grafana можно добавить БД Prometheus для анализа тех или иных событий ,произошедших во время сбора метрик.

   Все эти шаги мы рассмотрим поэтапно в нашем руководстве.

   Процесс установки протестирован на Ubuntu 22.04

   Во время установки, в скриптах можно поменять версию  сервисов на более свежую, сверившись с gihub разработчика.

   
   ![image](https://github.com/user-attachments/assets/2f985b8f-e970-4db4-b46e-da86ce97f03a)

