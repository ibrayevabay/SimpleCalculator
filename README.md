# SimpleCalculator
Calculator with DB

- Использовал layout-land Orientation, для смены ориентации. 
- Для адаптивности использовал linear layout  и назначил виджет элементам weight растянув их пропорционально.
- чтобы не терять значения при смене экрана передавал значения через Bundle SavedInstanceState
- результат сохраняет при каждом нажатии одной из кнопок + - * \ при помощи SqLiteDataBaseHelper'a
- прогружаю из базы данных при нажатии на кнопку History и при переходе на новый activity. Данные передаю в простой listView

*** Примечания
Над дизайном не заморачивался. Постарался решить указанные проблемы и побыстрее отправить их вам. Спасибо за просмотр!
***


