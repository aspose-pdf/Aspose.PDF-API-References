---
title: OperatorSelector
second_title: 用于 Java API 参考的 Aspose.PDF
description: 该类用于使用Visitor模板思想选择算子。
type: docs
weight: 234
url: /zh/java/com.aspose.pdf/operatorselector/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
[com.aspose.pdf.IOperatorSelector](../../com.aspose.pdf/ioperatorselector)
```
public final class OperatorSelector implements IOperatorSelector
```

该类用于使用Visitor模板思想选择算子。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [OperatorSelector()](#OperatorSelector--) | 初始化 Selector 类的新实例。 |
| [OperatorSelector(Operator op)](#OperatorSelector-com.aspose.pdf.Operator-) | 初始化新的 OperatorSelector 。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getSelected()](#getSelected--) | 选定对象的列表。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [visit(BDC BDC)](#visit-com.aspose.pdf.operators.BDC-) | 访问/选择 BDC 运营商。 |
| [visit(BI BI)](#visit-com.aspose.pdf.operators.BI-) | 访问/选择 BI 操作员。 |
| [visit(BMC BMC)](#visit-com.aspose.pdf.operators.BMC-) | 访问/选择 BMC 运营商。 |
| [visit(BT BT)](#visit-com.aspose.pdf.operators.BT-) | 访问/选择 BT 运营商。 |
| [visit(BX BX)](#visit-com.aspose.pdf.operators.BX-) | 访问/选择 BX 运营商。 |
| [visit(Clip W)](#visit-com.aspose.pdf.operators.Clip-) | 访问/选择 W 运算符。 |
| [visit(ClosePath h)](#visit-com.aspose.pdf.operators.ClosePath-) | 访问/选择 h 运算符。 |
| [visit(ClosePathEOFillStroke b_)](#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-) | 访问/选择 b\* 操作员。 |
| [visit(ClosePathFillStroke b)](#visit-com.aspose.pdf.operators.ClosePathFillStroke-) | 访问/选择 b 运算符。 |
| [visit(ClosePathStroke s)](#visit-com.aspose.pdf.operators.ClosePathStroke-) | 访问/选择 s 运算符。 |
| [visit(ConcatenateMatrix cm)](#visit-com.aspose.pdf.operators.ConcatenateMatrix-) | 访问/选择 cm 运算符。 |
| [visit(CurveTo c)](#visit-com.aspose.pdf.operators.CurveTo-) | 访问/选择 c 运算符。 |
| [visit(CurveTo1 v)](#visit-com.aspose.pdf.operators.CurveTo1-) | 访问/选择 v 运算符。 |
| [visit(CurveTo2 y)](#visit-com.aspose.pdf.operators.CurveTo2-) | 访问/选择 y 运算符。 |
| [visit(DP DP)](#visit-com.aspose.pdf.operators.DP-) | 访问/选择 DP 操作员。 |
| [visit(Do Do)](#visit-com.aspose.pdf.operators.Do-) | 访问/选择 Do 运算符。 |
| [visit(EI EI)](#visit-com.aspose.pdf.operators.EI-) | 访问/选择 EI 运营商。 |
| [visit(EMC EMC)](#visit-com.aspose.pdf.operators.EMC-) | 访问/选择 EMC 运营商。 |
| [visit(EOClip W_)](#visit-com.aspose.pdf.operators.EOClip-) | 访问/选择 W\* 操作员。 |
| [visit(EOFill f_)](#visit-com.aspose.pdf.operators.EOFill-) | 访问/选择运算符 f\*。 |
| [visit(EOFillStroke B_)](#visit-com.aspose.pdf.operators.EOFillStroke-) | 访问/选择 B\* 操作员。 |
| [visit(ET ET)](#visit-com.aspose.pdf.operators.ET-) | 访问/选择 ET 操作员。 |
| [visit(EX EX)](#visit-com.aspose.pdf.operators.EX-) | 访问/选择 EX 操作员。 |
| [visit(EndPath n)](#visit-com.aspose.pdf.operators.EndPath-) | 访问/选择 n 运营商。 |
| [visit(Fill f)](#visit-com.aspose.pdf.operators.Fill-) | 访问/选择 f 运算符。 |
| [visit(FillStroke B)](#visit-com.aspose.pdf.operators.FillStroke-) | 访问/选择 B 操作员。 |
| [visit(GRestore Q)](#visit-com.aspose.pdf.operators.GRestore-) | 访问/选择 Q 运算符。 |
| [visit(GS gs)](#visit-com.aspose.pdf.operators.GS-) | 访问/选择 gs 操作员。 |
| [visit(GSave q)](#visit-com.aspose.pdf.operators.GSave-) | 访问/选择 q 运算符。 |
| [visit(ID ID)](#visit-com.aspose.pdf.operators.ID-) | 访问/选择 ID 运营商。 |
| [visit(LineTo l)](#visit-com.aspose.pdf.operators.LineTo-) | 访问/选择 l 运算符。 |
| [visit(MP MP)](#visit-com.aspose.pdf.operators.MP-) | 访问/选择 MP 操作员。 |
| [visit(MoveTextPosition Td)](#visit-com.aspose.pdf.operators.MoveTextPosition-) | 访问/选择 Td 运算符。 |
| [visit(MoveTextPositionSetLeading TD)](#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-) | 访问/选择 TD 运营商。 |
| [visit(MoveTo m)](#visit-com.aspose.pdf.operators.MoveTo-) | 访问/选择 m 运算符。 |
| [visit(MoveToNextLine T_)](#visit-com.aspose.pdf.operators.MoveToNextLine-) | 访问/选择 T\* 操作员。 |
| [visit(MoveToNextLineShowText value)](#visit-com.aspose.pdf.operators.MoveToNextLineShowText-) | 访问/选择 ' 运营商。 |
| [visit(ObsoleteFill F)](#visit-com.aspose.pdf.operators.ObsoleteFill-) | 访问/选择 F 运算符。 |
| [visit(Re re)](#visit-com.aspose.pdf.operators.Re-) | 访问/选择重新操作员。 |
| [visit(SelectFont Tf)](#visit-com.aspose.pdf.operators.SelectFont-) | 访问/选择 Tf 运算符。 |
| [visit(SetAdvancedColor scn)](#visit-com.aspose.pdf.operators.SetAdvancedColor-) | 访问/选择 scn 操作员。 |
| [visit(SetAdvancedColorStroke SCN)](#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-) | 访问/选择 SCN 运营商。 |
| [visit(SetCMYKColor k)](#visit-com.aspose.pdf.operators.SetCMYKColor-) | 访问/选择 k 运算符。 |
| [visit(SetCMYKColorStroke K)](#visit-com.aspose.pdf.operators.SetCMYKColorStroke-) | 访问/选择 K 运算符。 |
| [visit(SetCharWidth d0)](#visit-com.aspose.pdf.operators.SetCharWidth-) | 访问/选择 d0 运算符。 |
| [visit(SetCharWidthBoundingBox d1)](#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-) | 访问/选择 d1 操作员。 |
| [visit(SetCharacterSpacing Tc)](#visit-com.aspose.pdf.operators.SetCharacterSpacing-) | 访问/选择 Tc 运算符。 |
| [visit(SetColor sc)](#visit-com.aspose.pdf.operators.SetColor-) | 访问/选择 sc 操作员。 |
| [visit(SetColorRenderingIntent ri)](#visit-com.aspose.pdf.operators.SetColorRenderingIntent-) | 访问/选择 ri 运算符。 |
| [visit(SetColorSpace cs)](#visit-com.aspose.pdf.operators.SetColorSpace-) | 访问/选择 cs 运算符。 |
| [visit(SetColorSpaceStroke CS)](#visit-com.aspose.pdf.operators.SetColorSpaceStroke-) | 访问/选择 CS 运营商。 |
| [visit(SetColorStroke SC)](#visit-com.aspose.pdf.operators.SetColorStroke-) | 访问/选择 SC 运营商。 |
| [visit(SetDash d)](#visit-com.aspose.pdf.operators.SetDash-) | 访问/选择 d 运算符。 |
| [visit(SetFlat i)](#visit-com.aspose.pdf.operators.SetFlat-) | 访问/选择 i 运算符。 |
| [visit(SetGlyphsPositionShowText TJ)](#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-) | 访问/选择 TJ 运营商。 |
| [visit(SetGray g)](#visit-com.aspose.pdf.operators.SetGray-) | 访问/选择 g 运算符。 |
| [visit(SetGrayStroke G)](#visit-com.aspose.pdf.operators.SetGrayStroke-) | 访问/选择 G 运算符。 |
| [visit(SetHorizontalTextScaling Tz)](#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-) | 访问/选择 Tz 运算符。 |
| [visit(SetLineCap J)](#visit-com.aspose.pdf.operators.SetLineCap-) | 访问/选择 J 运算符。 |
| [visit(SetLineJoin j)](#visit-com.aspose.pdf.operators.SetLineJoin-) | 访问/选择 j 运算符。 |
| [visit(SetLineWidth w)](#visit-com.aspose.pdf.operators.SetLineWidth-) | 访问/选择 w 运算符。 |
| [visit(SetMiterLimit M)](#visit-com.aspose.pdf.operators.SetMiterLimit-) | 访问/选择 M 运算符。 |
| [visit(SetRGBColor rg)](#visit-com.aspose.pdf.operators.SetRGBColor-) | 访问/选择 rg 操作员。 |
| [visit(SetRGBColorStroke RG)](#visit-com.aspose.pdf.operators.SetRGBColorStroke-) | 访问/选择 RG 操作员。 |
| [visit(SetSpacingMoveToNextLineShowText value)](#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-) | 访问/选择“”运营商。 |
| [visit(SetTextLeading TL)](#visit-com.aspose.pdf.operators.SetTextLeading-) | 访问/选择 TL 操作员。 |
| [visit(SetTextMatrix Tm)](#visit-com.aspose.pdf.operators.SetTextMatrix-) | 访问/选择 Tm 操作员。 |
| [visit(SetTextRenderingMode Tr)](#visit-com.aspose.pdf.operators.SetTextRenderingMode-) | 访问/选择 Tr 运算符。 |
| [visit(SetTextRise Ts)](#visit-com.aspose.pdf.operators.SetTextRise-) | 访问/选择 Ts 运算符。 |
| [visit(SetWordSpacing Tw)](#visit-com.aspose.pdf.operators.SetWordSpacing-) | 访问/选择 Tw 运营商。 |
| [visit(ShFill sh)](#visit-com.aspose.pdf.operators.ShFill-) | 访问/选择 sh 运算符。 |
| [visit(ShowText Tj)](#visit-com.aspose.pdf.operators.ShowText-) | 访问/选择 Tj 运算符。 |
| [visit(Stroke S)](#visit-com.aspose.pdf.operators.Stroke-) | 访问/选择 S 运算符。 |
| [visit(TextOperator textOperator)](#visit-com.aspose.pdf.operators.TextOperator-) | 访问/选择任何文本运算符运算符。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### OperatorSelector() {#OperatorSelector--}
```
public OperatorSelector()
```


初始化 Selector 类的新实例。

### OperatorSelector(Operator op) {#OperatorSelector-com.aspose.pdf.Operator-}
```
public OperatorSelector(Operator op)
```


初始化新的 OperatorSelector 。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| op | [Operator](../../com.aspose.pdf/operator) | 要访问/选择的运算符。 |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getSelected() {#getSelected--}
```
public List<Operator> getSelected()
```


选定对象的列表。

**退货：**
java.util.List<com.aspose.pdf.Operator> - Operator 实例列表
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### visit(BDC BDC) {#visit-com.aspose.pdf.operators.BDC-}
```
public void visit(BDC BDC)
```


访问/选择 BDC 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| BDC | [BDC](../../com.aspose.pdf.operators/bdc) | 开始标记内容序列运算符（带有属性列表）。 |

### visit(BI BI) {#visit-com.aspose.pdf.operators.BI-}
```
public void visit(BI BI)
```


访问/选择 BI 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| BI | [BI](../../com.aspose.pdf.operators/bi) | 开始内联图像对象运算符。 |

### visit(BMC BMC) {#visit-com.aspose.pdf.operators.BMC-}
```
public void visit(BMC BMC)
```


访问/选择 BMC 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| BMC | [BMC](../../com.aspose.pdf.operators/bmc) | 开始标记内容序列运算符。 |

### visit(BT BT) {#visit-com.aspose.pdf.operators.BT-}
```
public void visit(BT BT)
```


访问/选择 BT 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| BT | [BT](../../com.aspose.pdf.operators/bt) | 开始文本对象运算符。 |

### visit(BX BX) {#visit-com.aspose.pdf.operators.BX-}
```
public void visit(BX BX)
```


访问/选择 BX 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| BX | [BX](../../com.aspose.pdf.operators/bx) | 开始兼容性部分运算符。 |

### visit(Clip W) {#visit-com.aspose.pdf.operators.Clip-}
```
public void visit(Clip W)
```


访问/选择 W 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| W | [Clip](../../com.aspose.pdf.operators/clip) | 设置剪切路径运算符（非零缠绕数规则）。 |

### visit(ClosePath h) {#visit-com.aspose.pdf.operators.ClosePath-}
```
public void visit(ClosePath h)
```


访问/选择 h 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| h | [ClosePath](../../com.aspose.pdf.operators/closepath) | 关闭子路径运算符。 |

### visit(ClosePathEOFillStroke b_) {#visit-com.aspose.pdf.operators.ClosePathEOFillStroke-}
```
public void visit(ClosePathEOFillStroke b_)
```


访问/选择 b\* 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| b_ | [ClosePathEOFillStroke](../../com.aspose.pdf.operators/closepatheofillstroke) | 闭合、填充和描边路径运算符（奇偶规则）。 |

### visit(ClosePathFillStroke b) {#visit-com.aspose.pdf.operators.ClosePathFillStroke-}
```
public void visit(ClosePathFillStroke b)
```


访问/选择 b 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| b | [ClosePathFillStroke](../../com.aspose.pdf.operators/closepathfillstroke) | 闭合、填充和描边路径运算符（非零缠绕数规则）。 |

### visit(ClosePathStroke s) {#visit-com.aspose.pdf.operators.ClosePathStroke-}
```
public void visit(ClosePathStroke s)
```


访问/选择 s 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| s | [ClosePathStroke](../../com.aspose.pdf.operators/closepathstroke) | 关闭和描边路径运算符。 |

### visit(ConcatenateMatrix cm) {#visit-com.aspose.pdf.operators.ConcatenateMatrix-}
```
public void visit(ConcatenateMatrix cm)
```


访问/选择 cm 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cm | [ConcatenateMatrix](../../com.aspose.pdf.operators/concatenatematrix) | 将矩阵连接到当前变换矩阵运算符。 |

### visit(CurveTo c) {#visit-com.aspose.pdf.operators.CurveTo-}
```
public void visit(CurveTo c)
```


访问/选择 c 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| c | [CurveTo](../../com.aspose.pdf.operators/curveto) | 将曲线段附加到路径运算符（三个控制点）。 |

### visit(CurveTo1 v) {#visit-com.aspose.pdf.operators.CurveTo1-}
```
public void visit(CurveTo1 v)
```


访问/选择 v 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| v | [CurveTo1](../../com.aspose.pdf.operators/curveto1) | 将曲线段附加到路径运算符（复制初始点）。 |

### visit(CurveTo2 y) {#visit-com.aspose.pdf.operators.CurveTo2-}
```
public void visit(CurveTo2 y)
```


访问/选择 y 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| y | [CurveTo2](../../com.aspose.pdf.operators/curveto2) | 将曲线段附加到路径运算符（复制终点）。 |

### visit(DP DP) {#visit-com.aspose.pdf.operators.DP-}
```
public void visit(DP DP)
```


访问/选择 DP 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| DP | [DP](../../com.aspose.pdf.operators/dp) | 定义标记内容点运算符（带有属性列表）。 |

### visit(Do Do) {#visit-com.aspose.pdf.operators.Do-}
```
public void visit(Do Do)
```


访问/选择 Do 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Do | [Do](../../com.aspose.pdf.operators/do) | 调用命名的 XObject 运算符。 |

### visit(EI EI) {#visit-com.aspose.pdf.operators.EI-}
```
public void visit(EI EI)
```


访问/选择 EI 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| EI | [EI](../../com.aspose.pdf.operators/ei) | 结束内联图像对象运算符。 |

### visit(EMC EMC) {#visit-com.aspose.pdf.operators.EMC-}
```
public void visit(EMC EMC)
```


访问/选择 EMC 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| EMC | [EMC](../../com.aspose.pdf.operators/emc) | 结束标记内容序列运算符。 |

### visit(EOClip W_) {#visit-com.aspose.pdf.operators.EOClip-}
```
public void visit(EOClip W_)
```


访问/选择 W\* 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| W_ | [EOClip](../../com.aspose.pdf.operators/eoclip) | 设置剪切路径运算符（奇偶规则）。 |

### visit(EOFill f_) {#visit-com.aspose.pdf.operators.EOFill-}
```
public void visit(EOFill f_)
```


访问/选择运算符 f\*。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| f_ | [EOFill](../../com.aspose.pdf.operators/eofill) | 填充路径运算符（奇偶规则）。 |

### visit(EOFillStroke B_) {#visit-com.aspose.pdf.operators.EOFillStroke-}
```
public void visit(EOFillStroke B_)
```


访问/选择 B\* 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| B_ | [EOFillStroke](../../com.aspose.pdf.operators/eofillstroke) | 填充和描边路径运算符（奇偶规则）。 |

### visit(ET ET) {#visit-com.aspose.pdf.operators.ET-}
```
public void visit(ET ET)
```


访问/选择 ET 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ET | [ET](../../com.aspose.pdf.operators/et) | 结束文本对象运算符。 |

### visit(EX EX) {#visit-com.aspose.pdf.operators.EX-}
```
public void visit(EX EX)
```


访问/选择 EX 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| EX | [EX](../../com.aspose.pdf.operators/ex) | 结束兼容性部分运算符。 |

### visit(EndPath n) {#visit-com.aspose.pdf.operators.EndPath-}
```
public void visit(EndPath n)
```


访问/选择 n 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| n | [EndPath](../../com.aspose.pdf.operators/endpath) | 结束路径运算符（没有填充或描边）。 |

### visit(Fill f) {#visit-com.aspose.pdf.operators.Fill-}
```
public void visit(Fill f)
```


访问/选择 f 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| f | [Fill](../../com.aspose.pdf.operators/fill) | 填充路径运算符（非零缠绕数规则）。 |

### visit(FillStroke B) {#visit-com.aspose.pdf.operators.FillStroke-}
```
public void visit(FillStroke B)
```


访问/选择 B 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| B | [FillStroke](../../com.aspose.pdf.operators/fillstroke) | 填充和描边路径运算符（非零缠绕数规则）。 |

### visit(GRestore Q) {#visit-com.aspose.pdf.operators.GRestore-}
```
public void visit(GRestore Q)
```


访问/选择 Q 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Q | [GRestore](../../com.aspose.pdf.operators/grestore) | 恢复图形状态运算符。 |

### visit(GS gs) {#visit-com.aspose.pdf.operators.GS-}
```
public void visit(GS gs)
```


访问/选择 gs 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| gs | [GS](../../com.aspose.pdf.operators/gs) | 设置图形状态运算符。 |

### visit(GSave q) {#visit-com.aspose.pdf.operators.GSave-}
```
public void visit(GSave q)
```


访问/选择 q 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| q | [GSave](../../com.aspose.pdf.operators/gsave) | 保存图形状态运算符。 |

### visit(ID ID) {#visit-com.aspose.pdf.operators.ID-}
```
public void visit(ID ID)
```


访问/选择 ID 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ID | [ID](../../com.aspose.pdf.operators/id) | 开始内联图像数据运算符。 |

### visit(LineTo l) {#visit-com.aspose.pdf.operators.LineTo-}
```
public void visit(LineTo l)
```


访问/选择 l 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| l | [LineTo](../../com.aspose.pdf.operators/lineto) | 将直线段附加到路径运算符。 |

### visit(MP MP) {#visit-com.aspose.pdf.operators.MP-}
```
public void visit(MP MP)
```


访问/选择 MP 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| MP | [MP](../../com.aspose.pdf.operators/mp) | 定义标记内容点运算符。 |

### visit(MoveTextPosition Td) {#visit-com.aspose.pdf.operators.MoveTextPosition-}
```
public void visit(MoveTextPosition Td)
```


访问/选择 Td 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Td | [MoveTextPosition](../../com.aspose.pdf.operators/movetextposition) | 移动文本位置运算符。 |

### visit(MoveTextPositionSetLeading TD) {#visit-com.aspose.pdf.operators.MoveTextPositionSetLeading-}
```
public void visit(MoveTextPositionSetLeading TD)
```


访问/选择 TD 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| TD | [MoveTextPositionSetLeading](../../com.aspose.pdf.operators/movetextpositionsetleading) | 移动文本位置并设置前导运算符。 |

### visit(MoveTo m) {#visit-com.aspose.pdf.operators.MoveTo-}
```
public void visit(MoveTo m)
```


访问/选择 m 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| m | [MoveTo](../../com.aspose.pdf.operators/moveto) | 开始新的子路径运算符。 |

### visit(MoveToNextLine T_) {#visit-com.aspose.pdf.operators.MoveToNextLine-}
```
public void visit(MoveToNextLine T_)
```


访问/选择 T\* 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| T_ | [MoveToNextLine](../../com.aspose.pdf.operators/movetonextline) | 移动到下一个文本行运算符的开头。 |

### visit(MoveToNextLineShowText value) {#visit-com.aspose.pdf.operators.MoveToNextLineShowText-}
```
public void visit(MoveToNextLineShowText value)
```


访问/选择 ' 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [MoveToNextLineShowText](../../com.aspose.pdf.operators/movetonextlineshowtext) | 移动到下一行并显示文本运算符。 |

### visit(ObsoleteFill F) {#visit-com.aspose.pdf.operators.ObsoleteFill-}
```
public void visit(ObsoleteFill F)
```


访问/选择 F 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| F | [ObsoleteFill](../../com.aspose.pdf.operators/obsoletefill) | 填充路径运算符（非零缠绕数规则）。 |

### visit(Re re) {#visit-com.aspose.pdf.operators.Re-}
```
public void visit(Re re)
```


访问/选择重新操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| re | [Re](../../com.aspose.pdf.operators/re) | 将矩形附加到路径运算符。 |

### visit(SelectFont Tf) {#visit-com.aspose.pdf.operators.SelectFont-}
```
public void visit(SelectFont Tf)
```


访问/选择 Tf 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Tf | [SelectFont](../../com.aspose.pdf.operators/selectfont) | 设置文本字体和大小运算符。 |

### visit(SetAdvancedColor scn) {#visit-com.aspose.pdf.operators.SetAdvancedColor-}
```
public void visit(SetAdvancedColor scn)
```


访问/选择 scn 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| scn | [SetAdvancedColor](../../com.aspose.pdf.operators/setadvancedcolor) | 设置颜色运算符（用于非描边操作、ICCBased 和特殊颜色空间）。 |

### visit(SetAdvancedColorStroke SCN) {#visit-com.aspose.pdf.operators.SetAdvancedColorStroke-}
```
public void visit(SetAdvancedColorStroke SCN)
```


访问/选择 SCN 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| SCN | [SetAdvancedColorStroke](../../com.aspose.pdf.operators/setadvancedcolorstroke) | 设置颜色运算符（用于描边操作、ICCBased 和特殊颜色空间）。 |

### visit(SetCMYKColor k) {#visit-com.aspose.pdf.operators.SetCMYKColor-}
```
public void visit(SetCMYKColor k)
```


访问/选择 k 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| k | [SetCMYKColor](../../com.aspose.pdf.operators/setcmykcolor) | 设置 CMYK 颜色运算符（用于非描边操作）。 |

### visit(SetCMYKColorStroke K) {#visit-com.aspose.pdf.operators.SetCMYKColorStroke-}
```
public void visit(SetCMYKColorStroke K)
```


访问/选择 K 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| K | [SetCMYKColorStroke](../../com.aspose.pdf.operators/setcmykcolorstroke) | 设置 CMYK 颜色运算符（用于描边操作）。 |

### visit(SetCharWidth d0) {#visit-com.aspose.pdf.operators.SetCharWidth-}
```
public void visit(SetCharWidth d0)
```


访问/选择 d0 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| d0 | [SetCharWidth](../../com.aspose.pdf.operators/setcharwidth) | 在 Type 3 字体运算符中设置字形宽度。 |

### visit(SetCharWidthBoundingBox d1) {#visit-com.aspose.pdf.operators.SetCharWidthBoundingBox-}
```
public void visit(SetCharWidthBoundingBox d1)
```


访问/选择 d1 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| d1 | [SetCharWidthBoundingBox](../../com.aspose.pdf.operators/setcharwidthboundingbox) | 在 Type 3 字体运算符中设置字形宽度和边界框。 |

### visit(SetCharacterSpacing Tc) {#visit-com.aspose.pdf.operators.SetCharacterSpacing-}
```
public void visit(SetCharacterSpacing Tc)
```


访问/选择 Tc 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Tc | [SetCharacterSpacing](../../com.aspose.pdf.operators/setcharacterspacing) | 设置字符间距运算符。 |

### visit(SetColor sc) {#visit-com.aspose.pdf.operators.SetColor-}
```
public void visit(SetColor sc)
```


访问/选择 sc 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sc | [SetColor](../../com.aspose.pdf.operators/setcolor) | 设置颜色运算符（用于非描边操作）。 |

### visit(SetColorRenderingIntent ri) {#visit-com.aspose.pdf.operators.SetColorRenderingIntent-}
```
public void visit(SetColorRenderingIntent ri)
```


访问/选择 ri 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| ri | [SetColorRenderingIntent](../../com.aspose.pdf.operators/setcolorrenderingintent) | 设置颜色渲染意图运算符。 |

### visit(SetColorSpace cs) {#visit-com.aspose.pdf.operators.SetColorSpace-}
```
public void visit(SetColorSpace cs)
```


访问/选择 cs 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| cs | [SetColorSpace](../../com.aspose.pdf.operators/setcolorspace) | 设置颜色空间运算符（用于非描边操作）。 |

### visit(SetColorSpaceStroke CS) {#visit-com.aspose.pdf.operators.SetColorSpaceStroke-}
```
public void visit(SetColorSpaceStroke CS)
```


访问/选择 CS 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| CS | [SetColorSpaceStroke](../../com.aspose.pdf.operators/setcolorspacestroke) | 设置颜色空间运算符（用于描边操作）。 |

### visit(SetColorStroke SC) {#visit-com.aspose.pdf.operators.SetColorStroke-}
```
public void visit(SetColorStroke SC)
```


访问/选择 SC 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| SC | [SetColorStroke](../../com.aspose.pdf.operators/setcolorstroke) | 设置颜色运算符（用于描边操作）。 |

### visit(SetDash d) {#visit-com.aspose.pdf.operators.SetDash-}
```
public void visit(SetDash d)
```


访问/选择 d 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| d | [SetDash](../../com.aspose.pdf.operators/setdash) | 设置线划线模式运算符。 |

### visit(SetFlat i) {#visit-com.aspose.pdf.operators.SetFlat-}
```
public void visit(SetFlat i)
```


访问/选择 i 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| i | [SetFlat](../../com.aspose.pdf.operators/setflat) | 设置平面度公差运算符。 |

### visit(SetGlyphsPositionShowText TJ) {#visit-com.aspose.pdf.operators.SetGlyphsPositionShowText-}
```
public void visit(SetGlyphsPositionShowText TJ)
```


访问/选择 TJ 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| TJ | [SetGlyphsPositionShowText](../../com.aspose.pdf.operators/setglyphspositionshowtext) | 显示文本运算符（允许单独的字形定位）。 |

### visit(SetGray g) {#visit-com.aspose.pdf.operators.SetGray-}
```
public void visit(SetGray g)
```


访问/选择 g 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| g | [SetGray](../../com.aspose.pdf.operators/setgray) | 设置灰度级运算符（用于非描边操作）。 |

### visit(SetGrayStroke G) {#visit-com.aspose.pdf.operators.SetGrayStroke-}
```
public void visit(SetGrayStroke G)
```


访问/选择 G 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| G | [SetGrayStroke](../../com.aspose.pdf.operators/setgraystroke) | 设置灰度级运算符（用于描边操作）。 |

### visit(SetHorizontalTextScaling Tz) {#visit-com.aspose.pdf.operators.SetHorizontalTextScaling-}
```
public void visit(SetHorizontalTextScaling Tz)
```


访问/选择 Tz 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Tz | [SetHorizontalTextScaling](../../com.aspose.pdf.operators/sethorizontaltextscaling) | 设置水平文本缩放运算符。 |

### visit(SetLineCap J) {#visit-com.aspose.pdf.operators.SetLineCap-}
```
public void visit(SetLineCap J)
```


访问/选择 J 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| J | [SetLineCap](../../com.aspose.pdf.operators/setlinecap) | 设置线帽样式运算符。 |

### visit(SetLineJoin j) {#visit-com.aspose.pdf.operators.SetLineJoin-}
```
public void visit(SetLineJoin j)
```


访问/选择 j 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| j | [SetLineJoin](../../com.aspose.pdf.operators/setlinejoin) | 设置线连接样式运算符。 |

### visit(SetLineWidth w) {#visit-com.aspose.pdf.operators.SetLineWidth-}
```
public void visit(SetLineWidth w)
```


访问/选择 w 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| w | [SetLineWidth](../../com.aspose.pdf.operators/setlinewidth) | 设置线宽运算符。 |

### visit(SetMiterLimit M) {#visit-com.aspose.pdf.operators.SetMiterLimit-}
```
public void visit(SetMiterLimit M)
```


访问/选择 M 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| M | [SetMiterLimit](../../com.aspose.pdf.operators/setmiterlimit) | 设置斜接限制运算符。 |

### visit(SetRGBColor rg) {#visit-com.aspose.pdf.operators.SetRGBColor-}
```
public void visit(SetRGBColor rg)
```


访问/选择 rg 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rg | [SetRGBColor](../../com.aspose.pdf.operators/setrgbcolor) | 设置 RGB 颜色运算符（用于非描边操作）。 |

### visit(SetRGBColorStroke RG) {#visit-com.aspose.pdf.operators.SetRGBColorStroke-}
```
public void visit(SetRGBColorStroke RG)
```


访问/选择 RG 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| RG | [SetRGBColorStroke](../../com.aspose.pdf.operators/setrgbcolorstroke) | 设置 RGB 颜色运算符（用于描边操作）。 |

### visit(SetSpacingMoveToNextLineShowText value) {#visit-com.aspose.pdf.operators.SetSpacingMoveToNextLineShowText-}
```
public void visit(SetSpacingMoveToNextLineShowText value)
```


访问/选择“”运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [SetSpacingMoveToNextLineShowText](../../com.aspose.pdf.operators/setspacingmovetonextlineshowtext) | 设置单词和字符间距，移动到下一行，并显示文本运算符。 |

### visit(SetTextLeading TL) {#visit-com.aspose.pdf.operators.SetTextLeading-}
```
public void visit(SetTextLeading TL)
```


访问/选择 TL 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| TL | [SetTextLeading](../../com.aspose.pdf.operators/settextleading) | 设置文本前导运算符。 |

### visit(SetTextMatrix Tm) {#visit-com.aspose.pdf.operators.SetTextMatrix-}
```
public void visit(SetTextMatrix Tm)
```


访问/选择 Tm 操作员。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Tm | [SetTextMatrix](../../com.aspose.pdf.operators/settextmatrix) | 设置文本矩阵和文本行矩阵运算符。 |

### visit(SetTextRenderingMode Tr) {#visit-com.aspose.pdf.operators.SetTextRenderingMode-}
```
public void visit(SetTextRenderingMode Tr)
```


访问/选择 Tr 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Tr | [SetTextRenderingMode](../../com.aspose.pdf.operators/settextrenderingmode) | 设置文本渲染模式运算符。 |

### visit(SetTextRise Ts) {#visit-com.aspose.pdf.operators.SetTextRise-}
```
public void visit(SetTextRise Ts)
```


访问/选择 Ts 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Ts | [SetTextRise](../../com.aspose.pdf.operators/settextrise) | 设置文本上升运算符。 |

### visit(SetWordSpacing Tw) {#visit-com.aspose.pdf.operators.SetWordSpacing-}
```
public void visit(SetWordSpacing Tw)
```


访问/选择 Tw 运营商。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Tw | [SetWordSpacing](../../com.aspose.pdf.operators/setwordspacing) | 设置字间距运算符。 |

### visit(ShFill sh) {#visit-com.aspose.pdf.operators.ShFill-}
```
public void visit(ShFill sh)
```


访问/选择 sh 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| sh | [ShFill](../../com.aspose.pdf.operators/shfill) | 由着色模式运算符定义的绘制区域。 |

### visit(ShowText Tj) {#visit-com.aspose.pdf.operators.ShowText-}
```
public void visit(ShowText Tj)
```


访问/选择 Tj 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| Tj | [ShowText](../../com.aspose.pdf.operators/showtext) | 显示文本运算符。 |

### visit(Stroke S) {#visit-com.aspose.pdf.operators.Stroke-}
```
public void visit(Stroke S)
```


访问/选择 S 运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| S | [Stroke](../../com.aspose.pdf.operators/stroke) | 笔划路径运算符。 |

### visit(TextOperator textOperator) {#visit-com.aspose.pdf.operators.TextOperator-}
```
public void visit(TextOperator textOperator)
```


访问/选择任何文本运算符运算符。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| textOperator | [TextOperator](../../com.aspose.pdf.operators/textoperator) | 通用文本运算符，用于选择相应的 pdf 运算符集。 |

### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
