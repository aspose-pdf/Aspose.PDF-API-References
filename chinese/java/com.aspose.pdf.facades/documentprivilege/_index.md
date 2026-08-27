---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Aspose.PDF for Java API 参考"
description: "表示访问 Pdf 文件的权限。参见{@code PdfFileSecurity}。使用此类有 4 种方式：1.直接使用预定义的权限。2.基于 a。"
type: docs
weight: 110
url: /zh/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

表示访问 Pdf 文件的权限。参见 {@code PdfFileSecurity}。使用此类有 4 种方式：1.直接使用预定义的权限。2.基于预定义的权限并更改某些特定权限。3.基于预定义的权限并更改某些特定的 Adobe Professional 权限组合。4.混合方式 2 和方式 3。 //Way1: Using predefined privilege directly. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Based on a predefined privilege and change some specifical permissions. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Mixes the way2 and way3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | 比较两个 {@code DocumentPrivilege} 对象。 |
| [equals](#equals-java.lang.Object-) | 指示另一个对象是否与此对象“相等”。 <p> <code>equals</code> 方法在非空对象引用上实现等价关系： <ul> <li>它是 <i>自反的</i>：对于任何非空引用值 <code>x</code>，<code>x.equals(x)</code> 应返回 <code>true</code>。 <li>它是 <i>对称的</i>：对于任何非空引用值 <code>x</code> 和 <code>y</code>，<code>x.equals(y)</code> 应返回 <code>true</code> 当且仅当 <code>y.equals(x)</code> 返回 <code>true</code>。 <li>它是 <i>传递的</i>：对于任何非空引用值 <code>x</code>、<code>y</code> 和 <code>z</code>，如果 <code>x.equals(y)</code> 返回 <code>true</code> 且 <code>y.equals(z)</code> 返回 <code>true</code>，则 <code>x.equals(z</code>) 应返回 <code>true</code>。 <li>它是一致的：对于任何非空引用值 <code>x</code> 和 <code>y</code>，多次调用 <tt>x.equals(y)</tt> 始终返回 <code>true</code> 或始终返回 <code>false</code>，前提是用于 <code>equals</code> 比较的对象信息未被修改。 <li>对于任何非空引用值 <code>x</code>，<code>x.equals(null)</code> 应返回 <code>false</code>。 </ul> <p> 类 <code>Object</code> 的 <tt>equals</tt> 方法实现了对象上最严格的等价关系；也就是说，对于任何非空引用值 <code>x</code> 和 <code>y</code>，仅当 <code>x</code> 与 <code>y</code> 引用同一对象（<code>x == y</code> 的值为 <code>true</code>）时，此方法才返回 <code>true</code>。 <p> 请注意，通常在覆盖此方法时也需要覆盖 <tt>hashCode</tt> 方法，以维护 <tt>hashCode</tt> 方法的一般约定，即相等的对象必须具有相等的哈希码。 |
| [getAllowAll](#getAllowAll--) | 全部允许。 |
| [getAssembly](#getAssembly--) | 允许组装文件。 |
| [getChangeAllowLevel](#getChangeAllowLevel--) | 获取和设置文档权限的更改级别。与 Adobe Professional 的“允许更改”设置相同。0：无。1：插入、删除和旋转页面。2：填写表单字段并签署已有的签名字段。3：添加批注、填写表单字段并签署已有的签名字段。4：除提取页面外的所有操作。如果属性值为 -1，则级别未定义。 |
| [getCopy](#getCopy--) | 允许复制文件。 |
| [getCopyAllowLevel](#getCopyAllowLevel--) | 获取和设置文档权限的复制级别。与 Adobe Professional 的权限设置相同。0：无。1：为视障人士的屏幕阅读设备启用文本访问。2：启用文本、图像和其他内容的复制。如果属性值为 -1，则级别未定义。 |
| [getDegradedPrinting](#getDegradedPrinting--) | 允许低质量打印。 |
| [getFillIn](#getFillIn--) | 允许在文件中填写表单。 |
| [getForbidAll](#getForbidAll--) | 全部禁止。 |
| [getModifyAnnotations](#getModifyAnnotations--) | 允许修改文件的注释。 |
| [getModifyContents](#getModifyContents--) | 允许修改文件。 |
| [getPrint](#getPrint--) | 允许打印文件。 |
| [getPrintAllowLevel](#getPrintAllowLevel--) | 获取和设置文档权限的打印级别。与 Adobe Professional 的“允许打印”设置相同。0：无。1：低分辨率（150 dpi）。2：高分辨率。如果属性值为 -1，则级别未定义。 |
| [getScreenReaders](#getScreenReaders--) | 仅允许在屏幕上阅读。 |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | 返回对象的哈希码值。此方法支持哈希表（例如由 <code>java.util.Hashtable</code> 提供的哈希表）。<p> <code>hashCode</code> 的一般约定是：<ul> <li>在 Java 应用程序的执行期间，如果在同一对象上多次调用它，<tt>hashCode</tt> 方法必须始终返回相同的整数，前提是用于对象的 <tt>equals</tt> 比较的信息未被修改。该整数在一次执行与另一执行之间不必保持一致。<li>如果两个对象根据 <tt>equals(Object)</tt> 方法相等，则对这两个对象调用 <code>hashCode</code> 方法必须产生相同的整数结果。<li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 <tt>hashCode</tt> 方法必须产生不同的整数结果。然而，程序员应注意，为不相等的对象产生不同的整数结果可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，由类 <tt>Object</tt> 定义的 hashCode 方法确实会为不同的对象返回不同的整数。（这通常通过将对象的内部地址转换为整数实现，但 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言并未要求此实现技术。） |
| [isAllowAssembly](#isAllowAssembly--) | 设置是否允许程序集的权限。true 表示允许，false 表示禁止。 |
| [isAllowCopy](#isAllowCopy--) | 设置是否允许复制的权限。true 表示允许，false 表示禁止。 |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | 设置是否允许降级打印的权限。true 表示允许，false 表示禁止。设置后，打印将限制为外观的低级表示，可能质量下降。 |
| [isAllowFillIn](#isAllowFillIn--) | 设置是否允许填写表单的权限。true 表示允许，false 表示禁止。 |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | 设置是否允许修改注释的权限。true 表示允许，false 表示禁止。 |
| [isAllowModifyContents](#isAllowModifyContents--) | 设置是否允许修改内容的权限。true 表示允许，false 表示禁止。 |
| [isAllowPrint](#isAllowPrint--) | 设置是否允许打印的权限。true 表示允许，false 表示禁止。 |
| [isAllowScreenReaders](#isAllowScreenReaders--) | 设置是否允许屏幕阅读器的权限。true 表示允许，false 表示禁止。 |
| [setAllowAssembly](#setAllowAssembly-boolean-) | 设置是否允许程序集的权限。true 表示允许，false 表示禁止。 |
| [setAllowCopy](#setAllowCopy-boolean-) | 设置是否允许复制的权限。true 表示允许，false 表示禁止。 |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | 设置是否允许降级打印的权限。true 表示允许，false 表示禁止。设置后，打印将限制为外观的低级表示，可能质量下降。 |
| [setAllowFillIn](#setAllowFillIn-boolean-) | 设置是否允许填写表单的权限。true 表示允许，false 表示禁止。 |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | 设置是否允许修改注释的权限。true 表示允许，false 表示禁止。 |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | 设置是否允许修改内容的权限。true 表示允许，false 表示禁止。 |
| [setAllowPrint](#setAllowPrint-boolean-) | 设置是否允许打印的权限。true 表示允许，false 表示禁止。 |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | 设置是否允许屏幕阅读器的权限。true 表示允许，false 表示禁止。 |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | 获取和设置文档权限的更改级别。与 Adobe Professional 的“允许更改”设置相同。0：无。1：插入、删除和旋转页面。2：填写表单字段并签署已有的签名字段。3：添加批注、填写表单字段并签署已有的签名字段。4：除提取页面外的所有操作。如果属性值为 -1，则级别未定义。 |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | 获取和设置文档权限的复制级别。与 Adobe Professional 的权限设置相同。0：无。1：为视障人士的屏幕阅读设备启用文本访问。2：启用文本、图像和其他内容的复制。如果属性值为 -1，则级别未定义。 |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | 获取和设置文档权限的打印级别。与 Adobe Professional 的“允许打印”设置相同。0：无。1：低分辨率（150 dpi）。2：高分辨率。如果属性值为 -1，则级别未定义。 |

### compareTo {#compareTo-java.lang.Object-}
比较两个 {@code DocumentPrivilege} 对象。

### equals {#equals-java.lang.Object-}
指示另一个对象是否与此对象“相等”。 <p> <code>equals</code> 方法在非空对象引用上实现等价关系： <ul> <li>它是 <i>自反的</i>：对于任何非空引用值 <code>x</code>，<code>x.equals(x)</code> 应返回 <code>true</code>。 <li>它是 <i>对称的</i>：对于任何非空引用值 <code>x</code> 和 <code>y</code>，<code>x.equals(y)</code> 应返回 <code>true</code> 当且仅当 <code>y.equals(x)</code> 返回 <code>true</code>。 <li>它是 <i>传递的</i>：对于任何非空引用值 <code>x</code>、<code>y</code> 和 <code>z</code>，如果 <code>x.equals(y)</code> 返回 <code>true</code> 且 <code>y.equals(z)</code> 返回 <code>true</code>，则 <code>x.equals(z</code>) 应返回 <code>true</code>。 <li>它是一致的：对于任何非空引用值 <code>x</code> 和 <code>y</code>，多次调用 <tt>x.equals(y)</tt> 始终返回 <code>true</code> 或始终返回 <code>false</code>，前提是用于 <code>equals</code> 比较的对象信息未被修改。 <li>对于任何非空引用值 <code>x</code>，<code>x.equals(null)</code> 应返回 <code>false</code>。 </ul> <p> 类 <code>Object</code> 的 <tt>equals</tt> 方法实现了对象上最严格的等价关系；也就是说，对于任何非空引用值 <code>x</code> 和 <code>y</code>，仅当 <code>x</code> 与 <code>y</code> 引用同一对象（<code>x == y</code> 的值为 <code>true</code>）时，此方法才返回 <code>true</code>。 <p> 请注意，通常在覆盖此方法时也需要覆盖 <tt>hashCode</tt> 方法，以维护 <tt>hashCode</tt> 方法的一般约定，即相等的对象必须具有相等的哈希码。

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

全部允许。

**Returns:**
DocumentPrivilege 元素

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

允许组装文件。

**Returns:**
DocumentPrivilege 元素

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

获取和设置文档权限的更改级别。与 Adobe Professional 的“允许更改”设置相同。0：无。1：插入、删除和旋转页面。2：填写表单字段并签署已有的签名字段。3：添加批注、填写表单字段并签署已有的签名字段。4：除提取页面外的所有操作。如果属性值为 -1，则级别未定义。

**Returns:**
int 值

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

允许复制文件。

**Returns:**
DocumentPrivilege 元素

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

获取和设置文档权限的复制级别。与 Adobe Professional 的权限设置相同。0：无。1：为视障人士的屏幕阅读设备启用文本访问。2：启用文本、图像和其他内容的复制。如果属性值为 -1，则级别未定义。

**Returns:**
int 值

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

允许低质量打印。

**Returns:**
DocumentPrivilege 元素

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

允许在文件中填写表单。

**Returns:**
DocumentPrivilege 元素

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

全部禁止。

**Returns:**
DocumentPrivilege 元素

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

允许修改文件的注释。

**Returns:**
DocumentPrivilege 元素

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

允许修改文件。

**Returns:**
DocumentPrivilege 元素

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

允许打印文件。

**Returns:**
DocumentPrivilege 元素

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

获取和设置文档权限的打印级别。与 Adobe Professional 的“允许打印”设置相同。0：无。1：低分辨率（150 dpi）。2：高分辨率。如果属性值为 -1，则级别未定义。

**Returns:**
int 值

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

仅允许在屏幕上阅读。

**Returns:**
DocumentPrivilege 元素

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

返回对象的哈希码值。此方法支持哈希表（例如由 <code>java.util.Hashtable</code> 提供的哈希表）。<p> <code>hashCode</code> 的一般约定是：<ul> <li>在 Java 应用程序的执行期间，如果在同一对象上多次调用它，<tt>hashCode</tt> 方法必须始终返回相同的整数，前提是用于对象的 <tt>equals</tt> 比较的信息未被修改。该整数在一次执行与另一执行之间不必保持一致。<li>如果两个对象根据 <tt>equals(Object)</tt> 方法相等，则对这两个对象调用 <code>hashCode</code> 方法必须产生相同的整数结果。<li>并<em>不</em>要求如果两个对象根据 {@link java.lang.Object#equals(java.lang.Object)} 方法不相等，则对这两个对象调用 <tt>hashCode</tt> 方法必须产生不同的整数结果。然而，程序员应注意，为不相等的对象产生不同的整数结果可能会提升哈希表的性能。 </ul> <p> 在合理可行的范围内，由类 <tt>Object</tt> 定义的 hashCode 方法确实会为不同的对象返回不同的整数。（这通常通过将对象的内部地址转换为整数实现，但 Java<span style="font-size:70%"><sup>TM</sup></span> 编程语言并未要求此实现技术。）

**Returns:**
此对象的哈希码值。@see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

设置是否允许程序集的权限。true 表示允许，false 表示禁止。

**Returns:**
布尔值

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

设置是否允许复制的权限。true 表示允许，false 表示禁止。

**Returns:**
布尔值

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

设置是否允许降级打印的权限。true 表示允许，false 表示禁止。设置后，打印将限制为外观的低级表示，可能质量下降。

**Returns:**
布尔值

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

设置是否允许填写表单的权限。true 表示允许，false 表示禁止。

**Returns:**
布尔值

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

设置是否允许修改注释的权限。true 表示允许，false 表示禁止。

**Returns:**
布尔值

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

设置是否允许修改内容的权限。true 表示允许，false 表示禁止。

**Returns:**
布尔值

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

设置是否允许打印的权限。true 表示允许，false 表示禁止。

**Returns:**
布尔值

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

设置是否允许屏幕阅读器的权限。true 表示允许，false 表示禁止。

**Returns:**
布尔值

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

设置是否允许程序集的权限。true 表示允许，false 表示禁止。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

设置是否允许复制的权限。true 表示允许，false 表示禁止。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

设置是否允许降级打印的权限。true 表示允许，false 表示禁止。设置后，打印将限制为外观的低级表示，可能质量下降。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

设置是否允许填写表单的权限。true 表示允许，false 表示禁止。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

设置是否允许修改注释的权限。true 表示允许，false 表示禁止。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

设置是否允许修改内容的权限。true 表示允许，false 表示禁止。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

设置是否允许打印的权限。true 表示允许，false 表示禁止。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

设置是否允许屏幕阅读器的权限。true 表示允许，false 表示禁止。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

获取和设置文档权限的更改级别。与 Adobe Professional 的“允许更改”设置相同。0：无。1：插入、删除和旋转页面。2：填写表单字段并签署已有的签名字段。3：添加批注、填写表单字段并签署已有的签名字段。4：除提取页面外的所有操作。如果属性值为 -1，则级别未定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

获取和设置文档权限的复制级别。与 Adobe Professional 的权限设置相同。0：无。1：为视障人士的屏幕阅读设备启用文本访问。2：启用文本、图像和其他内容的复制。如果属性值为 -1，则级别未定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

获取和设置文档权限的打印级别。与 Adobe Professional 的“允许打印”设置相同。0：无。1：低分辨率（150 dpi）。2：高分辨率。如果属性值为 -1，则级别未定义。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值 |
