# user-ip-php

d$_SERVER['REMOTE_ADDR']
$_SERVER['HTTP_USER_AGENT']
IP и клиент-браузер, соответственно

Определить IP адрес клиента, от которого пришел запрос, можно только одним единственным способом: $ip = $_SERVER['REMOTE_ADDR']; Все остальное к IP адресу не имеет никакого отношения.
Все значения массива $_SERVER, начинающиеся на 'HTTP_', являются заголовками запроса, которые клиент формирует полностью сам, как ему заблагорассудится.
