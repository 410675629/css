##display����
+ ����ֵ��none,block,inline-blok     none��Ԫ�ز�ռ�ռ�
+ inline-blockԪ�أ�a span
+ blockԪ��:div p header footer
 
 ##����
 ```css
 div{
    max-width:500px;
    margin:0 auto;
 }
 ```
 �����ڿ��С��div��Ȼ����ˮƽ��������max-width���Կ��Խ��������
 
 ##��ģ��
 margin,padding,border
 ```css
 div{
    width:200px;
    margin:0 auto;
    padding:20px;
    -webkit-box-sizing:border-box;
    -moz-box-sizing:border-box;
    box-sizing:border-box;
 }
 ```
 ÿ�μ����ȵ�ʱ�� Ҫ����padding border��ֵ ��box-sizing�����Ժ󣬿������Ϊ���پ��Ƕ���
 box-sizing֧�������ie8+
 
 ##position���� 
 Ĭ����static relative absolute fixed
 �У�top left right bottom
 relative�����������λ��  ��϶���ᱻ�
 fixed:����Ӵ� ��϶���
 absolute:��Ե�һ����Ϊstatic��λ�ĸ�Ԫ�� ���û�������ĸ�Ԫ�� �����bodyԪ�أ����һ���ҳ����������� ** ������ **
 
 ##float����
 
*���������ֻ���ͼƬ*

##clear����
clear:left �������Ԫ��������������󸡶� ʹ�Լ��ڸ���Ԫ�ص��·�

##ý���ѯ
```css
@media screen and (min-width:600px){
    
}
@media screen and (max-width:599px){
}
```

##inline-block��float
���������棺inline-block��float����  float��Ҫclear

+ vertical-align��Ӱ�쵽inline-blockԪ�� Ԫ�����»��м�� ��Ҫ����vertical-align:top;
+ ���ÿ��
+ ���Ԫ�أ�html��ǩ��֮���пո�ᵼ��Ԫ�أ���Ⱦ��֮���м�϶

##column-count��column-gap
```css3
.three-column{
    padding:1em;
    -moz-column-count:3;
    -moz-column-gap:1em;
    -webkit-column-count:3;
    -webkit-column-gap:1em;
    column-count:3;
    column-gap:1em;
}
```
##flexbox����
```css3
.container{
    display:-webkit-flex;
    display:flex;
}
.initial{
    -webkit-flex:initial;
    flex:initial;
    width:200px;
    min-width:100px;
}
.none{
    -webkit-flex:none;
    flex:none;
    width:200px;
}
.flex1{
    -webkit-flex:1;
    flex:1;
}
.flex2{
    -webkit-flex:2;
    flex:2;
}

```
*flexbox��ֱ���в���*
```css3
.vertical-container{
    height:300px;
    display:-webkit-flex;
    display:flex;
    -webkit-align-items:center;
    align-items:center;
    -webkit-justify-content:center;
    justify-content:center;
}
```
