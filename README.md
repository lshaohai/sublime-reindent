### sublime 格式化代码快捷键设置
```s
    sublime中自建的有格式化按钮：

    Edit  ->  Line  ->  Reindent  
    

    只是sublime并没有给他赋予快捷键，所以只需加上快捷键即可

    
    Preference  ->  Key Bindings -user 


    打开用户快捷键绑定设置添加(比如添加：alt + shift + f)


    [{ "keys": ["ctrl+alt+l"], "command": "reindent" }, ]  //注意不要忘记加逗号

    注:
        1. 这里为了和 vscode 保持一致就把格式化代码的快捷键设置成  alt + shift + f
        2. 如果已经设置过 快捷键，外边已经有 [] 就不需要加 [] ,如果是第一次设置 就需要 [] 不然不会生肖
```

```s
sublime text3 是一款 非常适合前端开发的 编辑器

ctrl + n 新建文件
ctrl + l 选中整行
ctrl + shift + l 选中 已选中的所有行

多行编辑
	1. 按住鼠标中键，不放，拖动。
	2. ctrl + 鼠标左键

vscode ：
	1. ctrl + 鼠标左键 拖动
	2. alt + 鼠标左键

```
[学习地址](https://ke.qq.com/webcourse/index.html#course_id=242173&term_id=100285656&taid=1594077112152573&vid=i1421chgfox)

#### 快速打开 sublime
```s
 1. 找到安装路径。 就是 你的 sublime 的安装路径
    比如我的是：
    D:\Program Files\Sublime Text 3
 2. 把这个路径 放入到环境变量中  [自行百度]
    
 3. cmd 中 输入 $ subl . 即可打开 sublime
```

#### 自动生成 自适应 viewport
[ sublime text 3 插件：自定义Emmet语法规则以快速输出bootstrap组件](https://github.com/lshaohai/sublime-reindent.git)


#### 快捷键 打开浏览器

[Sublime Text设置快捷键让html文件在浏览器打开](https://jingyan.baidu.com/article/adc815137f9ae2f723bf73ff.html)

#### 增加一个快捷键，删除当前标签，比如所在的标签

```
  ctrl + shift + ;
    
```

#### sublime 创建 文件 && 文件夹 的方法
```s
    1. 在当前目录下创建一个文件
        Ctrl + n   
    2.在文件夹 src/components/  下 创建一个 about 文件夹 以及在 about 下创建一个 About.vue 文件
        Ctrl + alt + n  ，然后输入 src/components/about/About.vue  

```
#### 自动补全文件路径 插件

```s
    1. Ctrl + shift + p
    2. 输入 install package  回车
    3. 输入 autofilename 回车
```
[参考](https://jingyan.baidu.com/article/a3aad71af1da97b1fa009650.html)