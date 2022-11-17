---
title: HideAction
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示隐藏操作，通过设置或清除其隐藏标志在屏幕上隐藏或显示一个或多个注释。
type: docs
weight: 152
url: /zh/java/com.aspose.pdf/hideaction/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.PdfAction](../../com.aspose.pdf/pdfaction)
```
public class HideAction extends PdfAction
```

表示隐藏操作，通过设置或清除其隐藏标志在屏幕上隐藏或显示一个或多个注释。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [HideAction(Annotation annotation)](#HideAction-com.aspose.pdf.Annotation-) | 为指定注释初始化 HideAction 类的新实例。 |
| [HideAction(Annotation annotation, boolean isHidden)](#HideAction-com.aspose.pdf.Annotation-boolean-) | 为指定的注释和不可见标志初始化 HideAction 类的新实例。 |
| [HideAction(String fieldName)](#HideAction-java.lang.String-) | 为指定的字段名称初始化 HideAction 类的新实例。 |
| [HideAction(String fieldName, boolean isHidden)](#HideAction-java.lang.String-boolean-) | 为指定的字段名称和不可见标志初始化 HideAction 类的新实例。 |
| [HideAction(Annotation[] annotations)](#HideAction-com.aspose.pdf.Annotation---) | 为指定注释初始化 HideAction 类的新实例。 |
| [HideAction(Annotation[] annotations, boolean isHidden)](#HideAction-com.aspose.pdf.Annotation---boolean-) | 为指定的注释和不可见标志初始化 HideAction 类的新实例。 |
| [HideAction(String[] names)](#HideAction-java.lang.String---) | 为指定的字段名称初始化 HideAction 类的新实例。 |
| [HideAction(String[] names, boolean isHidden)](#HideAction-java.lang.String---boolean-) | 为指定的字段名称和不可见标志初始化 HideAction 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getNext()](#getNext--) | 接下来的动作依次进行。 |
| [hashCode()](#hashCode--) |  |
| [isHidden()](#isHidden--) | 获取或设置注释的状态以隐藏/显示。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setHidden(boolean value)](#setHidden-boolean-) | 获取或设置注释的状态以隐藏/显示。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HideAction(Annotation annotation) {#HideAction-com.aspose.pdf.Annotation-}
```
public HideAction(Annotation annotation)
```


为指定注释初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 要隐藏的注释。 |

### HideAction(Annotation annotation, boolean isHidden) {#HideAction-com.aspose.pdf.Annotation-boolean-}
```
public HideAction(Annotation annotation, boolean isHidden)
```


为指定的注释和不可见标志初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotation | [Annotation](../../com.aspose.pdf/annotation) | 要隐藏或显示的注释。 |
| isHidden | boolean | 指示是隐藏注释 (true) 还是显示注释 (false) 的标志。 |

### HideAction(String fieldName) {#HideAction-java.lang.String-}
```
public HideAction(String fieldName)
```


为指定的字段名称初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 一个文本字符串，给出交互式表单字段的完全限定字段名称。 |

### HideAction(String fieldName, boolean isHidden) {#HideAction-java.lang.String-boolean-}
```
public HideAction(String fieldName, boolean isHidden)
```


为指定的字段名称和不可见标志初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 一个文本字符串，给出交互式表单字段的完全限定字段名称。 |
| isHidden | boolean | 指示是隐藏字段 (true) 还是显示字段 (false) 的标志。 |

### HideAction(Annotation[] annotations) {#HideAction-com.aspose.pdf.Annotation---}
```
public HideAction(Annotation[] annotations)
```


为指定注释初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotations | [Annotation\[\]](../../com.aspose.pdf/annotation) | 要隐藏的注释数组。 |

### HideAction(Annotation[] annotations, boolean isHidden) {#HideAction-com.aspose.pdf.Annotation---boolean-}
```
public HideAction(Annotation[] annotations, boolean isHidden)
```


为指定的注释和不可见标志初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| annotations | [Annotation\[\]](../../com.aspose.pdf/annotation) | 要隐藏或显示的一组注释。 |
| isHidden | boolean | 指示是隐藏注释 (true) 还是显示注释 (false) 的标志。 |

### HideAction(String[] names) {#HideAction-java.lang.String---}
```
public HideAction(String[] names)
```


为指定的字段名称初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| names | java.lang.String[] | 一个字符串数组，给出交互式表单字段的完全限定字段名称。 |

### HideAction(String[] names, boolean isHidden) {#HideAction-java.lang.String---boolean-}
```
public HideAction(String[] names, boolean isHidden)
```


为指定的字段名称和不可见标志初始化 HideAction 类的新实例。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| names | java.lang.String[] | 一个字符串数组，给出交互式表单字段的完全限定字段名称。 |
| isHidden | boolean | 指示是隐藏字段 (true) 还是显示字段 (false) 的标志。 |

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
### getNext() {#getNext--}
```
public ActionCollection getNext()
```


接下来的动作依次进行。

**退货：**
[ActionCollection](../../com.aspose.pdf/actioncollection) 动作集合对象
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isHidden() {#isHidden--}
```
public boolean isHidden()
```


获取或设置注释的状态以隐藏/显示。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setHidden(boolean value) {#setHidden-boolean-}
```
public void setHidden(boolean value)
```


获取或设置注释的状态以隐藏/显示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

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
