Learn github
===
1、github中创建一个帐号
---
#一级标题
##二级标题  
###三级标题  
####四级标题  
#####五级标题  
######六级标题  

这是一段普通的文本，Enter不能实现回车
<br>要使用\<br>
[百度](http://www.baidu.com)
[github官网](https://github.com "鼠标悬停显示github")

     单行框
     多行框
     两者都是使用两个Tab

`高亮显示文件`

* 昵称:清晨漫步
* 姓名:王朵荣
* 英文:Andy

* 一级原点
    * 二级原点
        * 三级原点

>数据结构
>>树
>>>二叉树
>>>>平衡二叉树

![百度log](http://www.baidu.com/img/bdlogo.gif)
![github项目中的图片](https://github.com/wdrgithub/javaLearn/blob/master/picture/1.jpg "github测试图")

```Java
public static void main(String[] args) {

        List<ODSInterface> odsInterfaceList = new ArrayList<>();
        ODSInterface odsInterface = new ODSInterface();
        odsInterface.setRatioStock(new BigDecimal(100));
        odsInterfaceList.add(odsInterface);
        if (CollectionUtils.isNotEmpty(odsInterfaceList)) {
            odsInterfaceList = JSONArray.parseArray(
                    JsonMapper.JSON_NON_EMPTY_MAPPER.toJson(odsInterfaceList), ODSInterface.class);
        }

        System.out.println(odsInterfaceList.get(0).getRatioStock());
}
```
