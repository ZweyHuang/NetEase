# CSS
### 媒体查询
#### 1. min-width+max-width

### 一、图片超出居中问题
#### 1. 绝对定位+2D变换
- 优点： 代码量少，自适应元素宽度
- 缺点： 兼容IE9+，transform变换耗性能

#### 2. 增加隐藏HTML结构
- 优点：兼容性好，可自适应元素宽度
- 缺点：多余的HTML结构

#### 3. 绝对定位+负外边距
- 优点：兼容性好，代码量少，不需要增加多余结构
- 缺点：需要预先知道元素宽度，不可自适应元素宽度

### 二、元素水平垂直居中
#### 1. 绝对定位+2D变换 
- 优点：可自适应，代码量少
- 缺点：兼容性不好，2D变换导致字体模糊问题

#### 2. 绝对定位+宽高+外边距
- 优点：可自适应，兼容性好
- 缺点：固定元素宽高，代码量略大

#### 3. 表结构
- 优点：可自适应，兼容性好
- 缺点：代码量大，多余代码

### 三、半透明兼容
#### 1. IE使用滤镜