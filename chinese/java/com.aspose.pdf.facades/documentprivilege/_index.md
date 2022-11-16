---
title: DocumentPrivilege
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示访问 Pdf 文件的权限。
type: docs
weight: 19
url: /zh/java/com.aspose.pdf.facades/documentprivilege/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Comparable
```
public final class DocumentPrivilege implements Comparable<Object>
```

表示访问 Pdf 文件的权限。请参阅 PdfFileSecurity 。使用该类有4种方式： 1.直接使用预定义的权限。 2.基于预定义的权限，更改一些特定的权限。 3.基于预定义权限并更改一些特定的Adobe Professional 权限组合。 4.混合方式2和方式3。

--------------------

```
//方式一：直接使用预定义权限。
  DocumentPrivilege privilege = DocumentPrivilege.getPrint();
  //Way2：基于预定义的权限，改变一些特定的权限。
  DocumentPrivilege privilege = DocumentPrivilege.getAllowAll();
  privilege.setAllowPrint(false);
  privilege.setAllowModifyContents(false);
  //Way3：基于预定义的权限和更改一些特定的 Adobe Professional 权限组合。
  DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
  privilege.setChangeAllowLevel(1);
  privilege.setPrintAllowLevel(2);
  //方式4：混合方式2和方式3
  DocumentPrivilege privilege = DocumentPrivilege.getForbidAll();
  privilege.setChangeAllowLevel(1);
  privilege.setAllowPrint(true);
```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [DocumentPrivilege(int value)](#DocumentPrivilege-int-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | 比较两个 DocumentPrivilege 对象。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指示某个其他对象是否“等于”这个对象。 |
| [getAllowAll()](#getAllowAll--) | 都允许。 |
| [getAssembly()](#getAssembly--) | 允许汇编文件。 |
| [getClass()](#getClass--) |  |
| [getCopy()](#getCopy--) | 允许复制文件。 |
| [getDegradedPrinting()](#getDegradedPrinting--) | 允许降级打印。 |
| [getFillIn()](#getFillIn--) | 允许在文件中填写表格。 |
| [getForbidAll()](#getForbidAll--) | 全部禁止。 |
| [getModifyAnnotations()](#getModifyAnnotations--) | 允许修改文件的注释。 |
| [getModifyContents()](#getModifyContents--) | 允许修改文件。 |
| [getPrint()](#getPrint--) | 允许打印文件。 |
| [getScreenReaders()](#getScreenReaders--) | 只允许在屏幕上阅读。 |
| [getValue()](#getValue--) | 获取价值 |
| [hashCode()](#hashCode--) | 返回对象的哈希码值。 |
| [isAllowAssembly()](#isAllowAssembly--) | 设置是否允许组装的权限。 true 是允许的，false 是禁止的。 |
| [isAllowCopy()](#isAllowCopy--) | 设置允许或不允许复制的权限。 true 是允许的，false 是禁止的。 |
| [isAllowDegradedPrinting()](#isAllowDegradedPrinting--) | 设置是否允许降级打印的权限。 true 是允许的，false 是禁止的。 |
| [isAllowFillIn()](#isAllowFillIn--) | 设置允许或不允许填写表格的权限。 true 是允许的，false 是禁止的。 |
| [isAllowModifyAnnotations()](#isAllowModifyAnnotations--) | 设置允许或不允许修改注释的权限。 true 是允许的，false 是禁止的。 |
| [isAllowModifyContents()](#isAllowModifyContents--) | 设置允许或不允许修改内容的权限。 true 是允许的，false 是禁止的。 |
| [isAllowPrint()](#isAllowPrint--) | 设置是否允许打印的权限。 true 是允许的，false 是禁止的。 |
| [isAllowScreenReaders()](#isAllowScreenReaders--) | 设置允许或不允许屏幕阅读器的权限。 true 是允许的，false 是禁止的。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAllowAssembly(boolean value)](#setAllowAssembly-boolean-) | 设置是否允许组装的权限。 true 是允许的，false 是禁止的。 |
| [setAllowCopy(boolean value)](#setAllowCopy-boolean-) | 设置允许或不允许复制的权限。 true 是允许的，false 是禁止的。 |
| [setAllowDegradedPrinting(boolean value)](#setAllowDegradedPrinting-boolean-) | 设置是否允许降级打印的权限。 true 是允许的，false 是禁止的。 |
| [setAllowFillIn(boolean value)](#setAllowFillIn-boolean-) | 设置允许或不允许填写表格的权限。 true 是允许的，false 是禁止的。 |
| [setAllowModifyAnnotations(boolean value)](#setAllowModifyAnnotations-boolean-) | 设置允许或不允许修改注释的权限。 true 是允许的，false 是禁止的。 |
| [setAllowModifyContents(boolean value)](#setAllowModifyContents-boolean-) | 设置允许或不允许修改内容的权限。 true 是允许的，false 是禁止的。 |
| [setAllowPrint(boolean value)](#setAllowPrint-boolean-) | 设置是否允许打印的权限。 true 是允许的，false 是禁止的。 |
| [setAllowScreenReaders(boolean value)](#setAllowScreenReaders-boolean-) | 设置允许或不允许屏幕阅读器的权限。 true 是允许的，false 是禁止的。 |
| [setChangeAllowLevel(int value)](#setChangeAllowLevel-int-) | 设置文档权限的更改级别。 |
| [setCopyAllowLevel(int value)](#setCopyAllowLevel-int-) | 设置文档权限的复制级别。 |
| [setPrintAllowLevel(int value)](#setPrintAllowLevel-int-) | 设置文档权限的打印级别。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### DocumentPrivilege(int value) {#DocumentPrivilege-int-}
```
public DocumentPrivilege(int value)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 文档的权限 |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public int compareTo(Object obj)
```


比较两个 DocumentPrivilege 对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与之比较的对象。 |

**退货：**
int - 一个带符号的整数，表示此实例和值的相对值。小于零，此实例小于值。零此实例等于值。大于零，此实例大于值。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指示某个其他对象是否“等于”这个对象。

这`equals`方法在非空对象引用上实现等价关系：

 *  这是*reflexive* ：对于任何非空参考值`x`, `x.equals(x)`应该返回`true`.
 *  这是*symmetric*：对于任何非空参考值`x`和`y`, `x.equals(y)`应该返回`true`当且仅当`y.equals(x)`回报`true`.
 *  这是*transitive*：对于任何非空参考值`x`, `y`， 和`z`， 如果`x.equals(y)`回报`true`和`y.equals(z)`回报`true`， 然后`x.equals(z)`应该返回`true`.
 *  这是*consistent*：对于任何非空参考值`x`和`y` 多次调用 x.equals(y) 始终返回`true`或持续返回`false`，只要没有信息用于`equals`修改对象的比较。
 *  对于任何非空参考值`x`, `x.equals(null)`应该返回`false`.

类的equals方法`Object`在对象上实现最具辨别力的可能等价关系；也就是说，对于任何非空引用值`x`和`y` 这个方法返回`true`当且仅当`x`和`y`引用同一个对象（`x == y`有价值`true`).

请注意，通常需要在重写此方法时重写 hashCode 方法，以维护 hashCode 方法的一般契约，该契约规定相等的对象必须具有相等的哈希码。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要与之比较的参考对象。 |

**退货：**
布尔值 -`true`如果此对象与 obj 参数相同；`false`否则。
### getAllowAll() {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```


都允许。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getAssembly() {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```


允许汇编文件。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getCopy() {#getCopy--}
```
public static DocumentPrivilege getCopy()
```


允许复制文件。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getDegradedPrinting() {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```


允许降级打印。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getFillIn() {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```


允许在文件中填写表格。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getForbidAll() {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```


全部禁止。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getModifyAnnotations() {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```


允许修改文件的注释。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getModifyContents() {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```


允许修改文件。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getPrint() {#getPrint--}
```
public static DocumentPrivilege getPrint()
```


允许打印文件。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getScreenReaders() {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```


只允许在屏幕上阅读。

**退货：**
[DocumentPrivilege](../../com.aspose.pdf.facades/documentprivilege) - DocumentPrivilege 元素
### getValue() {#getValue--}
```
public int getValue()
```


获取价值

**退货：**
int - 整数值
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回对象的哈希码值。支持此方法是为了哈希表的好处，例如由`java.util.Hashtable`.

的总合同`hashCode`是：

 *  每当在 Java 应用程序的执行期间对同一对象多次调用它时，hashCode 方法必须一致地返回相同的整数，前提是在对象的 equals 比较中使用的信息没有被修改。从一个应用程序的一次执行到同一应用程序的另一次执行，该整数不需要保持一致。
 *  如果根据 equals(Object) 方法两个对象相等，则调用`hashCode`两个对象中的每一个对象上的方法都必须产生相同的整数结果。
 *  这是*not*要求如果两个对象根据 java.lang.Object 不相等\#equals(java.lang.Object).equals(java.lang.Object) 方法，然后在两个对象中的每一个上调用 hashCode 方法必须产生不同的整数结果。但是，程序员应该意识到，为不相等的对象生成不同的整数结果可能会提高哈希表的性能。

在相当实用的情况下，类 Object 定义的 hashCode 方法确实会为不同的对象返回不同的整数。 （这通常是通过将对象的内部地址转换为整数来实现的，但 JavaTM 编程语言不需要这种实现技术。）

**退货：**
int - 此对象的哈希码值。
### isAllowAssembly() {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```


设置是否允许组装的权限。 true 是允许的，false 是禁止的。

**退货：**
boolean - 布尔值
### isAllowCopy() {#isAllowCopy--}
```
public boolean isAllowCopy()
```


设置允许或不允许复制的权限。 true 是允许的，false 是禁止的。

**退货：**
boolean - 布尔值
### isAllowDegradedPrinting() {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```


设置是否允许降级打印的权限。 true 是允许的，false 是禁止的。

**退货：**
boolean - 布尔值
### isAllowFillIn() {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```


设置允许或不允许填写表格的权限。 true 是允许的，false 是禁止的。

**退货：**
boolean - 布尔值
### isAllowModifyAnnotations() {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```


设置允许或不允许修改注释的权限。 true 是允许的，false 是禁止的。

**退货：**
boolean - 布尔值
### isAllowModifyContents() {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```


设置允许或不允许修改内容的权限。 true 是允许的，false 是禁止的。

**退货：**
boolean - 布尔值
### isAllowPrint() {#isAllowPrint--}
```
public boolean isAllowPrint()
```


设置是否允许打印的权限。 true 是允许的，false 是禁止的。

**退货：**
boolean - 布尔值
### isAllowScreenReaders() {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```


设置允许或不允许屏幕阅读器的权限。 true 是允许的，false 是禁止的。

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




### setAllowAssembly(boolean value) {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```


设置是否允许组装的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAllowCopy(boolean value) {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```


设置允许或不允许复制的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAllowDegradedPrinting(boolean value) {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```


设置是否允许降级打印的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAllowFillIn(boolean value) {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```


设置允许或不允许填写表格的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAllowModifyAnnotations(boolean value) {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```


设置允许或不允许修改注释的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAllowModifyContents(boolean value) {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```


设置允许或不允许修改内容的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAllowPrint(boolean value) {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```


设置是否允许打印的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAllowScreenReaders(boolean value) {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```


设置允许或不允许屏幕阅读器的权限。 true 是允许的，false 是禁止的。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setChangeAllowLevel(int value) {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```


设置文档权限的更改级别。正如 Adobe Professional 的 Changes Allowed 设置一样。 0：无。 1：插入、删除和旋转页面。 2：填写表单字段并签署现有签名字段。 3：评论、填写表单域和签署现有签名域。 4：除提取页面外的任何。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setCopyAllowLevel(int value) {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```


设置文档权限的复制级别。正如Adobe Professional 的权限设置一样。 0：无。 1：为视障人士启用屏幕阅读器设备的文本访问。 2：允许复制文字、图片等内容。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

### setPrintAllowLevel(int value) {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```


设置文档权限的打印级别。正如 Adobe Professional 的 Printing Allowed 设置一样。 0：无。 1：低分辨率 (150 dpi)。 2：高分辨率。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值 |

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
