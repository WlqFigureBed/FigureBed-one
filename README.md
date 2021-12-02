# Github PicGo Typora 实现MarkDown跨平台图片
## Github提供图床
- 构建一个仓库FigureBed-one

- 得到tokens：https://github.com/settings/tokens

  ![image-20200710145021618](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20200722121343.png)

![image-20200710150130436](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20200722121356.png)
只需要勾选repo即可！

## PicGo

![image-20210710143018194](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20210710143025.png)

>  github图片链接为：https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20210710143025.png
>
>  设置自定义域名：   https://github.com/WlqFigureBed/FigureBed-one/raw/master
>
>  - WlqFigureBed为用户名
>  - FigureBed-one为仓库名
>  - **raw：用于代替blob，否则无法正常显示！**
>  - master分支名，此处写主分支即可
>  - 20200710132336是时间戳命名的图片名
>
>  设定Token：https://github.com/settings/tokens

**最好开启时间戳重命名：**

![时间戳重命名](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20200722121435.png)

## Typora

![typora](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20200722121415.png)

## 上传失败怎么办？

### 一、检查server的端口是否正确

![设置server](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20210710143428.png)

![设置server](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/20210710143426.png)

### 二、设置代理

代理的端口可以从科学上网的工具获得，设置即可：

![设置代理和镜像地址](https://github.com/WlqFigureBed/FigureBed-one/raw/master/img/202112021640030.png)

**如果不行，可以先关闭Server，保存后再打开Server试试看。**

