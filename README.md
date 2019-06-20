React-Native-Template代码模版

在React-Native日常开发中，新建文件或者组件是最常用的操作,并且,组件内部的一些方法(页面跳转,组件监听等)也是重复来写。
可是，在我们新建不同的文件或者组件时，一些代码固定不变，此时，需要重新写一遍就费事费力了，而最常用的操作就是复制，粘贴，修改，重复而无趣。若是不想重复如此无聊的机械动作，又想快速高效的来完成任务，编写代码，那怎么办呢？此时，解决方案出现了。--File and Code Templates

使用此配置，可减省重复无用的劳动力，真正提升效率。
如果你觉得有用，请点个赞，或者分享给其他朋友。

一：配置有两种方式(以mac配置为例)：
一：
1-： 选择Preferences;

2-：搜索框输入Templates;

3-：点击File and Code Templates

4-：选中JavaScript File

5-：删除里面的代码，把以下代码复制进去(此代码可以自定义,包括引入组件,方法,样式文件等)：
```
import React, { Component } from 'react';
import {
  StyleSheet,
  Text,
  View,
  Image,
} from 'react-native';

export default class  ${NAME}  extends Component {
  render() {
    return (
      <View style={styles.container}>
       
      </View>
    );
  }
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
  },
});
```
6-：点击Apply
示例图如下：

![06200126.gif](https://upload-images.jianshu.io/upload_images/4803284-c12f8892290b485c.gif?imageMogr2/auto-orient/strip)


二：
1-： 选择Preferences;

2-：搜索框输入Templates;

3-：点击File and Code Templates

4-：点击左上角“+”号按钮

示例图如下：
![06200131.gif](https://upload-images.jianshu.io/upload_images/4803284-2e08051b1f56d466.gif?imageMogr2/auto-orient/strip)


注意点：
1-：注意新建文件的名字，本例子中取名为:React-Native;

2-：注意Extension的输入框填写为js;


四：使用方式：

分为两种，与上面配置方式一一对应：
一：

1-：点击New ，选择Java Script File；

2-：输入新建文件的名字，并点击OK；

3-：查看新建文件内容为填写的模版内容

二：
1-：点击New ，选择React-Native文件类型(与使用第二中配置方式时新建的名字一一对应)；

2-：输入新建文件的名字，并点击OK；

3-：查看新建文件内容为填写的模版内容

使用效果截图：
![06200136.gif](https://upload-images.jianshu.io/upload_images/4803284-d851c7508c145c04.gif?imageMogr2/auto-orient/strip)



四:封装一些方法/组件使用模版快速生成

1-： 选择Preferences;

2-：搜索框输入Templates;

3-：点击Live Templates;

4-：点击左上角“+”号按钮

依据下面视频,分别填写相关代码:
![06200204.gif](https://upload-images.jianshu.io/upload_images/4803284-6caa6dd092b3ee8b.gif?imageMogr2/auto-orient/strip)



```
1-:this.props.navigation.navigate("");

2:<TouchableOpacity 
    style={styles.}
    onPress={()=>{
    
}}>
    
</TouchableOpacity>


3-:{this.data..map=(item,index)=>{
                    return(
                        <View>
                        
                        </View>
                    )
=}}
```


使用:

![06200313.gif](https://upload-images.jianshu.io/upload_images/4803284-b9af94916c1d616f.gif?imageMogr2/auto-orient/strip)



以上,可根据自身业务进行相关调整和修改!!!!!

使用此配置，可减省重复无用的劳动力，真正提升效率。


若需要添加组件或代码,请下方留言,等后期添加完成可以下载。


同时,也提供了一份导出文件,可直接倒入使用:
[https://github.com/erhutime/React-Native-Template](https://github.com/erhutime/React-Native-Template)



