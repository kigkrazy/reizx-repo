### 使用方法

在gralde的repositories添加我们的仓库地址
```
repositories {  
	jcenter()  
	maven { 
		url "https://raw.githubusercontent.com/kigkrazy/reizx-repo/master" 
	}  
  }  
```

### 库说明
#### andrutil
这是一个工具类库，里面包含了许多常用的加密解密，IO等一些操常用的工具类。[仓库地址及说明](https://github.com/kigkrazy/andrutil)

引用方法  
```
	compile 'com.reizx:andrutil:1.7.0'
```

#### [luaj](https://github.com/kigkrazy/luaj-android)
JAVA平台的lua解析库，根据luaj项目修改，修改了部分android的BUG。

引用方法  
```
	compile 'com.reizx:luaj-jse:3.0.11'
```

### 更新日志

#### 2018年2月12日09:10:19
* 更新andrutil的依赖库版本