# TIL
오늘 공부하는 것을 기록하는 공간 

## 2020/10/25
오늘 heroku의 앱을 바꾼 뒤 github에서 로그인이 되지않아 하루 종일 콜백 url 땜에 시간을 날렸다 원인은 정말 어이없었는데 
`heroku config:push`를 해도 정작 heroku안에서는 바뀌지 않아서 계속 전의 app url로 요청을 보내 당연히 Internal Server Error가 발생했다. 
> 앞으로는 직접 들어가서 바뀌었는지 확인하자