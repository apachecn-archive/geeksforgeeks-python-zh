# Python PIL 属性| Image.height 方法

> 原文:[https://www . geesforgeks . org/pyhton-pil-attributes-image-height-method/](https://www.geeksforgeeks.org/pyhton-pil-attributes-image-height-method/)

PIL 是 python 图像库，它为 Python 解释器提供图像编辑功能。`Image`模块提供了一个同名的类，用于表示 PIL 图像。该模块还提供了许多工厂功能，包括从文件加载图像和创建新图像的功能。

`**Image**`类具有高度属性。

**`Image.height`** 图像高度，以像素为单位。属性定义了对象、元素或文件的各种属性。

> **语法:** PIL。图像.高度
> 
> **参数:**
> **图像**–图像用于不同的延伸。
> 
> **返回:**图像的高度

**所用图像:**
![](img/7dcee0f4c2b8e9d23dccc651065d73ab.png)

```

# importing Image module from PIL package 
from PIL import Image 

# opening a  image 
im = Image.open(r"C:\Users\System-Pc\Desktop\flower1.jpg") 

# height attribute
im1 = im.height
print(im1)
```

**输出:**

```
225

```

**另一个例子:**用拍摄另一个图像。png 扩展名。

**所用图像:**
![](img/686ce0abe8be10b924d2c483da582a22.png)

```

# importing Image module from PIL package 
from PIL import Image 

# opening a  image 
im = Image.open(r"C:\Users\System-Pc\Desktop\python.png") 

# height attribute
im1 = im.height
print(im1)
```

**输出:**

```
149

```