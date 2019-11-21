exception
     - 최상위 exception을 써도 되는데 왜 하위 exception을 사용하는가?
    - 하위의 exception은 최상위의 exception을 상속받아서 하기때문에 Exception 에 기능을 추가해서 사용하는것 
    - 최상위의 except 을 사용하면 다 잡을 수 있다.  정확한 exception의 이름으로 catch을 하면 좀더 기능적으로 잡을 수 있지만 빈틈을 만들지 않기 위해 최상위 exception를 사용한다.
    - exception을 사용하면 자신이 원하는 곳으로 데이터를 이동시킬 수 있기때문에 용이하게 throw를 사용할 수 있다.