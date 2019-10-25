# 04.null 과 undefined

Created: Aug 09, 2019 4:54 PM

JS에서는 '없음' 을 나타내는 값이 두 개 있는데, 바로 `null`과 `undefined` 가 있다.

두 값의 의미는 비슷하지만 각각 사용되는 목적과 장소가 다르다.

값이 대입되지 않은 변수 혹은 속성을 사용하려고 하면 undefined를 반환한다.

    let foo;
    foo // undefined
    
    const obj = {};
    obj.prop; // undefined

`null` 은 '객체가 없음'을 나타낸다. 실제로 typeof 연산을 해보면 아래와 같은 값을 반환한다. 

    typeof null // 'object'
    typeof undefined // 'undefined'

프로그래머의 입장에서 명시적으로 부재를 나타내고 싶다면 항상 null을 사용하는 것이 좋다. 다만, **객체를 사용할 때 어떤 속성의 부재를 null 을 통해서 나타내는 쪽보다는, 그냥 그 속성을 정의하지 않는 방식**이 간편하므로 더 널리 사용된다.

    // 이렇게 하는 경우는 드물다.
    {
    	name : 'horang',
    	age : null
    }
    
    // 그냥 아래와 같이 하는 경우가 많다.
    {
    	name: 'horang'
    }
    
    // 이렇게만은 하지말자
    {
    	name: 'horang',
    	age : undefined
    }

Null