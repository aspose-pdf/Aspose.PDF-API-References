---
title: AnnotationActionCollection
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示注释操作的集合。
type: docs
weight: 16
url: /zh/java/com.aspose.pdf/annotationactioncollection/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.BaseActionCollection](../../com.aspose.pdf/baseactioncollection)
```
public final class AnnotationActionCollection extends BaseActionCollection
```

表示注释操作的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getOnCalculate()](#getOnCalculate--) | 获取计算字段值的操作。 |
| [getOnClosePage()](#getOnClosePage--) | 获取关闭包含注释的页面时要执行的操作。 |
| [getOnEnter()](#getOnEnter--) | 获取当光标进入注释的活动区域时要执行的操作。 |
| [getOnExit()](#getOnExit--) | 获取当光标退出注释的活动区域时要执行的操作。 |
| [getOnFormat()](#getOnFormat--) | 获取要执行的操作以格式化字段值。 |
| [getOnHidePage()](#getOnHidePage--) | 获取当包含注释的页面在查看器应用程序的用户界面中不再可见时要执行的操作。 |
| [getOnLostFocus()](#getOnLostFocus--) | 获取当注释失去输入焦点时要执行的操作。 |
| [getOnModifyCharacter()](#getOnModifyCharacter--) | 获取当用户修改字段的字符时要执行的操作。 |
| [getOnOpenPage()](#getOnOpenPage--) | 获取打开包含注释的页面时要执行的操作。 |
| [getOnPressMouseBtn()](#getOnPressMouseBtn--) | 获取在注释的活动区域内按下鼠标按钮时要执行的操作。 |
| [getOnReceiveFocus()](#getOnReceiveFocus--) | 获取当注释接收到输入焦点时要执行的操作。 |
| [getOnReleaseMouseBtn()](#getOnReleaseMouseBtn--) | 获取在注释的活动区域内释放鼠标按钮时要执行的操作。 |
| [getOnShowPage()](#getOnShowPage--) | 获取当包含注释的页面在查看器应用程序的用户界面中可见时要执行的操作。 |
| [getOnValidate()](#getOnValidate--) | 获取当用户更改字段内容时要执行的操作。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeActions()](#removeActions--) | 删除注释的所有操作。 |
| [setOnCalculate(PdfAction value)](#setOnCalculate-com.aspose.pdf.PdfAction-) | 设置计算字段值的操作。 |
| [setOnClosePage(PdfAction value)](#setOnClosePage-com.aspose.pdf.PdfAction-) | 设置关闭包含注释的页面时要执行的操作。 |
| [setOnEnter(PdfAction value)](#setOnEnter-com.aspose.pdf.PdfAction-) | 设置当光标进入注释的活动区域时要执行的操作。 |
| [setOnExit(PdfAction value)](#setOnExit-com.aspose.pdf.PdfAction-) | 设置当光标离开注释的活动区域时要执行的操作。 |
| [setOnFormat(PdfAction value)](#setOnFormat-com.aspose.pdf.PdfAction-) | 设置要执行的操作以格式化字段值。 |
| [setOnHidePage(PdfAction value)](#setOnHidePage-com.aspose.pdf.PdfAction-) | 设置当包含注释的页面在查看器应用程序的用户界面中不再可见时要执行的操作。 |
| [setOnLostFocus(PdfAction value)](#setOnLostFocus-com.aspose.pdf.PdfAction-) | 设置注释失去输入焦点时要执行的操作。 |
| [setOnModifyCharacter(PdfAction value)](#setOnModifyCharacter-com.aspose.pdf.PdfAction-) | 设置当用户修改字段的字符时要执行的操作。 |
| [setOnOpenPage(PdfAction value)](#setOnOpenPage-com.aspose.pdf.PdfAction-) | 设置打开包含注释的页面时要执行的操作。 |
| [setOnPressMouseBtn(PdfAction value)](#setOnPressMouseBtn-com.aspose.pdf.PdfAction-) | 设置在注释的活动区域内按下鼠标按钮时要执行的操作。 |
| [setOnReceiveFocus(PdfAction value)](#setOnReceiveFocus-com.aspose.pdf.PdfAction-) | 设置注释接收到输入焦点时要执行的操作。 |
| [setOnReleaseMouseBtn(PdfAction value)](#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-) | 设置在注释的活动区域内释放鼠标按钮时要执行的操作。 |
| [setOnShowPage(PdfAction value)](#setOnShowPage-com.aspose.pdf.PdfAction-) | 设置当包含注释的页面在查看器应用程序的用户界面中可见时要执行的操作。 |
| [setOnValidate(PdfAction value)](#setOnValidate-com.aspose.pdf.PdfAction-) | 设置当用户更改字段内容时要执行的操作。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getOnCalculate() {#getOnCalculate--}
```
public PdfAction getOnCalculate()
```


获取计算字段值的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) - 计算字段值的操作。
### getOnClosePage() {#getOnClosePage--}
```
public PdfAction getOnClosePage()
```


获取关闭包含注释的页面时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnEnter() {#getOnEnter--}
```
public PdfAction getOnEnter()
```


获取当光标进入注释的活动区域时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnExit() {#getOnExit--}
```
public PdfAction getOnExit()
```


获取当光标退出注释的活动区域时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnFormat() {#getOnFormat--}
```
public PdfAction getOnFormat()
```


获取要执行的操作以格式化字段值。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) 要执行的操作以格式化字段值。
### getOnHidePage() {#getOnHidePage--}
```
public PdfAction getOnHidePage()
```


获取当包含注释的页面在查看器应用程序的用户界面中不再可见时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnLostFocus() {#getOnLostFocus--}
```
public PdfAction getOnLostFocus()
```


获取当注释失去输入焦点时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnModifyCharacter() {#getOnModifyCharacter--}
```
public PdfAction getOnModifyCharacter()
```


获取当用户修改字段的字符时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) - 当用户修改字段的字符时要执行的操作。
### getOnOpenPage() {#getOnOpenPage--}
```
public PdfAction getOnOpenPage()
```


获取打开包含注释的页面时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnPressMouseBtn() {#getOnPressMouseBtn--}
```
public PdfAction getOnPressMouseBtn()
```


获取在注释的活动区域内按下鼠标按钮时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnReceiveFocus() {#getOnReceiveFocus--}
```
public PdfAction getOnReceiveFocus()
```


获取当注释接收到输入焦点时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnReleaseMouseBtn() {#getOnReleaseMouseBtn--}
```
public PdfAction getOnReleaseMouseBtn()
```


获取在注释的活动区域内释放鼠标按钮时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnShowPage() {#getOnShowPage--}
```
public PdfAction getOnShowPage()
```


获取当包含注释的页面在查看器应用程序的用户界面中可见时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) -PdfAction 对象
### getOnValidate() {#getOnValidate--}
```
public PdfAction getOnValidate()
```


获取当用户更改字段内容时要执行的操作。

**退货：**
[PdfAction](../../com.aspose.pdf/pdfaction) - 用户更改字段内容时要执行的操作。
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




### removeActions() {#removeActions--}
```
public void removeActions()
```


删除注释的所有操作。

### setOnCalculate(PdfAction value) {#setOnCalculate-com.aspose.pdf.PdfAction-}
```
public void setOnCalculate(PdfAction value)
```


设置计算字段值的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | 计算字段值的操作。 |

### setOnClosePage(PdfAction value) {#setOnClosePage-com.aspose.pdf.PdfAction-}
```
public void setOnClosePage(PdfAction value)
```


设置关闭包含注释的页面时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnEnter(PdfAction value) {#setOnEnter-com.aspose.pdf.PdfAction-}
```
public void setOnEnter(PdfAction value)
```


设置当光标进入注释的活动区域时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnExit(PdfAction value) {#setOnExit-com.aspose.pdf.PdfAction-}
```
public void setOnExit(PdfAction value)
```


设置当光标离开注释的活动区域时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnFormat(PdfAction value) {#setOnFormat-com.aspose.pdf.PdfAction-}
```
public void setOnFormat(PdfAction value)
```


设置要执行的操作以格式化字段值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | 要执行的操作以格式化字段值。 |

### setOnHidePage(PdfAction value) {#setOnHidePage-com.aspose.pdf.PdfAction-}
```
public void setOnHidePage(PdfAction value)
```


设置当包含注释的页面在查看器应用程序的用户界面中不再可见时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnLostFocus(PdfAction value) {#setOnLostFocus-com.aspose.pdf.PdfAction-}
```
public void setOnLostFocus(PdfAction value)
```


设置注释失去输入焦点时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnModifyCharacter(PdfAction value) {#setOnModifyCharacter-com.aspose.pdf.PdfAction-}
```
public void setOnModifyCharacter(PdfAction value)
```


设置当用户修改字段的字符时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | 当用户修改字段的字符时要执行的操作。 |

### setOnOpenPage(PdfAction value) {#setOnOpenPage-com.aspose.pdf.PdfAction-}
```
public void setOnOpenPage(PdfAction value)
```


设置打开包含注释的页面时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnPressMouseBtn(PdfAction value) {#setOnPressMouseBtn-com.aspose.pdf.PdfAction-}
```
public void setOnPressMouseBtn(PdfAction value)
```


设置在注释的活动区域内按下鼠标按钮时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnReceiveFocus(PdfAction value) {#setOnReceiveFocus-com.aspose.pdf.PdfAction-}
```
public void setOnReceiveFocus(PdfAction value)
```


设置注释接收到输入焦点时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnReleaseMouseBtn(PdfAction value) {#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-}
```
public void setOnReleaseMouseBtn(PdfAction value)
```


设置在注释的活动区域内释放鼠标按钮时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnShowPage(PdfAction value) {#setOnShowPage-com.aspose.pdf.PdfAction-}
```
public void setOnShowPage(PdfAction value)
```


设置当包含注释的页面在查看器应用程序的用户界面中可见时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | PdfAction 对象 |

### setOnValidate(PdfAction value) {#setOnValidate-com.aspose.pdf.PdfAction-}
```
public void setOnValidate(PdfAction value)
```


设置当用户更改字段内容时要执行的操作。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [PdfAction](../../com.aspose.pdf/pdfaction) | 当用户更改字段内容时要执行的操作。 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
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
