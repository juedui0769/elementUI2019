参考 <https://blog.csdn.net/weixin_34403976/article/details/89469152> 

由于ESlint规范化，导致console.log的使用也会报错，下面是设置允许console.log控制台输出

描述：打开 package.json 文件，找到 rules 属性，加入以下代码

```
// rules这个属性默认是有的，如果没有那就自己添加至 eslintConfig 属性下
 "rules": {
 	// 这一行代码就是允许console.log 设置
    "no-console": "off"
  },
```
