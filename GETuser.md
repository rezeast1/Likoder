## GET /user
### Description
Запрашивает данные с сервера ФНС
### Parameters
| Name|Type|Description| 
|-----|----|-----------|
|     |    |           | 
### Responses
#### Code 200

successful operation

Media type:_application/json_

**Example Value:**<br>
``` {
{"items":[{"ИНН":"026616692810"}]}
```
#### Code 404
**Example Value:**<br>
```
{"items":[],"error":"Информация об ИНН не найдена.
 Рекомендуем проверить правильность введённых данных
 и повторить попытку поиска."}
```