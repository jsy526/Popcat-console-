# Popcat-console
팝캣을 빠르게 클릭 합니다.

> https://popcat.click/ 에 접속 합니다.

```

  var event = new KeyboardEvent('keydown', {	key: 'g',	ctrlKey: true}); setInterval(function(){	for (i = 0; i < 100; i++) {		document.dispatchEvent(event);	}}, 0);

 ```

 > 를 `f12` 키를 누르고 `console(큰솔)`을 눌러 밑에 칸에 넣어주고 `Enter(엔터)`를 눌러주면
 팝캣의 클릭이 자동으로 올라갑니다.

 

 > 이 레파스토지는 한국인을 위하여 번역 된 것 입니다
 원본: https://gist.github.com/DaWe35/0febd8b058e4476967d12675a622c989



   
 
 

 
 
 
 
 
 
