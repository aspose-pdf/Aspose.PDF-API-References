---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "此类包含定义 PdfContentEditor 在执行 ReplaceText 操作时行为的参数。"
type: docs
weight: 650
url: /zh/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

此类包含定义 PdfContentEditor 在执行 ReplaceText 操作时行为的参数。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | 当未找到适用于更改文本的合适字体时执行的操作（Throw exception / Substitute other font / Replace anyway）。 |
| [getReplaceScope](#getReplaceScope--) | 替换操作的范围（replace first occurence or replace all occurences）。 |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | 如果为 false，则要查找的字符串是普通文本。如果为 true，则要查找的字符串是正则表达式。 |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | 当未找到适用于更改文本的合适字体时执行的操作（Throw exception / Substitute other font / Replace anyway）。 |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | 如果为 false，则要查找的字符串是普通文本。如果为 true，则要查找的字符串是正则表达式。 |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | 替换操作的范围（replace first occurence or replace all occurences）。 |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

当未找到适用于更改文本的合适字体时执行的操作（Throw exception / Substitute other font / Replace anyway）。

**Returns:**
NoCharacterAction 值。 @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

替换操作的范围（replace first occurence or replace all occurences）。

**Returns:**
Scope 元素 @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

如果为 false，则要查找的字符串是普通文本。如果为 true，则要查找的字符串是正则表达式。

**Returns:**
布尔值

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
当未找到适用于更改文本的合适字体时执行的操作（Throw exception / Substitute other font / Replace anyway）。

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

如果为 false，则要查找的字符串是普通文本。如果为 true，则要查找的字符串是正则表达式。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
替换操作的范围（replace first occurence or replace all occurences）。
