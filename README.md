# Unity-UI-Rounded-Corners

这些组件和着色器可以让你为 UI 元素添加圆角！


---

![](title.gif)

## 如何安装
### 步骤 1：软件包管理器（Unity 2019.3 及更高版本）
![](how-to-install.gif)
要复制粘贴的网址：
```
https://github.com/Unity-GamerFrameWork/Unity-UI-Rounded-Corners.git
```

## 如何使用
#### 对称的圆形
- 为带有 `Image` 游戏对象添加 `ImageWithRoundedCorners` 组件
- 调整 `Radius` 属性
#### 每个角都具有一定的圆度值
- 将 `ImageWithIndependentRoundedCorners` 添加到带有 `Image` 游戏对象中
- 调整 `r` Vector4 属性。每个向量分量表示半径，顺时针方向，从左上角开始。
#### 特别注意
如果需要在运行时添加或更改图像，请 `Validate()` ，然后 `Refresh()` 来更新材质。


# Features
## 单独或一次性改变圆度
![](separate-roundness.gif)
## 调整尺寸时保持圆形
![](gif-01.gif)
## 比精灵图质量更好
![](image-00.png)
## 支持 Unity Mask
![](gif-02.gif)
## 支持着色
![](gif-04.gif)
