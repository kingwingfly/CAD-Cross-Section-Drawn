# 天正CAD立面、剖面图绘制

## 一、准备好各层平面图

![image-20220506163943543](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506163943543.png)

## 二、天正打开任一平面图

![image-20220506164103826](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506164103826.png)

## 三、新建工程管理文件

![image-20220506164558035](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506164558035.png)

建议保存到平面图们所在的目录

![image-20220506164751724](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506164751724.png)

## 四、打开并修改工程文件

1. 打开工程文件

   ![image-20220506164952633](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506164952633.png)

   ![image-20220506165429633](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506165429633.png)

2. 添加图纸与设置楼层

   （右键“平面图”即可添加图纸）

![image-20220506165807991](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506165807991.png)

## 五、生成三维模型（选做）

依次点击

![image-20220506170001965](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506170001965.png)

![image-20220506170034685](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506170034685.png)

![image-20220506170135164](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506170135164.png)

即得到模型：

![image-20220506170221215](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506170221215.png)

模型的查看操作：

1. 按住鼠标中键拖动可平移视角
2. shift+鼠标中键拖动可旋转视角
3. 左键单击此处修改渲染风格：

![image-20220506170445324](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506170445324.png)

## 六、立面图生成（以正立面为例）

1. 选择生成正立面

![image-20220506170843753](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506170843753.png)

2. 若选择轴线，则敲一下空格

![image-20220506170930955](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506170930955.png)

3. 进一步设置参数

   ![image-20220506171143292](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506171143292.png)

   命名保存

![](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506171212369.png)

## 七、立面图的整理

1. 删除轴线

   ![image-20220506171330778](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506171330778.png)

2. 加粗轮廓

3. 删除多余的标高

4. 删除难看的层高线

5. 删删删删删，难看的统统删掉。删掉，一定要删掉，，，，狂删。

   【删除技巧】：

   1. 若只能整体删除，可又不想整体删除，如：标高。可选中整体使用X命令，即可选择部分进行删除。
   2. 使用Trim命令（tr即可）删除。

6. 做法标注（建议使用“引出标注”，因为“做法标注”我不会）

   ![image-20220506172041508](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506172041508.png)

   **至此，效果如下：**

   ![image-20220506172113088](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506172113088.png)

   *地坪没加粗，我摆*

## 八、剖面图的绘制

1. 在平面图中添加剖切符号

   ![image-20220506172347252](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506172347252.png)

作业中为这两个位置：

![image-20220506172448668](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506172448668.png)

2. 生成剖面

![image-20220506172930581](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506172930581.png)

![image-20220506172959773](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506172959773.png)

![image-20220506173031537](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506173031537.png)

结果如下：

![image-20220506173157571](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506173157571.png)

之后处理方法与立面图相同。

tips：关于如何把立面与剖面放入一个文件中：可以选中后使用CTRL+C/V的方式复制粘贴。Mac应该可以的。

## 其它注意事项（重要或实用）

1. 关于楼道的窗户：需选中用Move上移1800（如图所示，为剖面图与侧立面图的窗）

![image-20220506173115702](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506173115702.png)

![image-20220506173719596](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506173719596.png)

2. 在楼梯其他中可以绘制阳台：

   ![image-20220506173857073](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506173857073.png)

3. 对剖立面图的标高，可以使用此命令对齐：

   ![image-20220506174006976](https://cdn.jsdelivr.net/gh/kingwingshit/Louis/img/image-20220506174006976.png)

4. 千万记得提交作业时用 tsaveas命令保存