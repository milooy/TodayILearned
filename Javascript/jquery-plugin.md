## jQuery Plugin 만들기
```javascript
(function($){

    // return : return 문을 사용하게 되면 이 플러그인을 다른 jQuery 메소드와 함께 자유롭게 체이닝을 사용할 수 있다.
    return this.each(function(){  // this 키워드 : jQuery 객체 자체를 나타낸다.

        var $el = $(this);  // each 내부에서 사용되는 this는 DOM요소를 차례로 가리킨다.

    });

})(jQuery) // 네임스페이스 보호
```
`jQuery.fn`은 `jQuery.prototype`의 간결 버전. jQuery 객체의 prototype 프로퍼티에 새로운 메서드로 추가됨.
