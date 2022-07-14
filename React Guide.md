App.js 내부에 컴포넌트 생성

컴포넌트는 최상위 태그하나만 포함(vue랑 동일)



props 상위 컴포넌트에서 하위 컴포넌트로 정보 전달

{this.props.변수}   



컴포넌트를 파일로 만들면    

```
import React, { Component } from 'react';

class 컴포넌트명 extends Component{
	render(){
		return (
			내용
		);
	}
}

export default Content;
```



메인파일에서

```
import 컴포넌트명 from "파일경로" 
```



props, state 변경 하는법 알기 

 
