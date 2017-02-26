## react-paint

一个涂鸦组件大概长这样 
![预览图](./gra.png)

实现功能:
-涂鸦功能
-撤销和前进以及保存为图片功能
-切换画笔大小和颜色功能

### 使用

将app/components复制进入项目中,需要有React,ReactDOM,url-loader,babel等包支持,例如
``` bash
import Graffiti from 'xxxx/Graffiti.jsx';
import React,{ Component } from 'xxxx/Graffiti.jsx';

class App extends Component{
	render(){
		return(
			<div>
				<Graffiti width={number} height={number} imgUrl={url}/>
			</div>
		)
	}
}
```

或者直接使用本项目
``` bash
npm install
npm start
```