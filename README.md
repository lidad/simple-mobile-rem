# 简单的移动端rem工具
此rem方案来自于某位大神的博客，copy下来在自己的项目里（吃水忘记挖井人，罪过罪过。。），用了很长时间都不错。

### 怎样使用
JS:
```
import rem from 'simple-mobile-rem';
rem();//默认基准字体大小为16px（iphone6设计图），其余两个参数可不填写

```
SASS:
```
//sass中建立rem.scss文件并写入仓库中rem.scss代码，注意$font与$screen皆是iphone6设计图尺寸
import 'rem.scss';
.wrap {
  width:px2rex(280);
}
```
