# Popcat-console-
팝캣을 빠르게 클릭 합니다.
> https://popcat.click/ 에 접속 합니다.

```var event = new KeyboardEvent('keydown', {	key: 'g',	ctrlKey: true}); setInterval(function(){	for (i = 0; i < 100; i++) {		document.dispatchEvent(event);	}}, 0);```
```
