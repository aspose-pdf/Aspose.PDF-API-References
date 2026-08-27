---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Aspose.PDF for Java API 参考"
description: "旨在将流式 RTF 内容提取为一组令牌的类。"
type: docs
weight: 40
url: /zh/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

旨在将流式 RTF 内容提取为一组令牌的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [readNextToken](#readNextToken--) | 读取输入流并返回下一个标记。 |
| [skip](#skip-int-) | 从输入流中消耗并丢弃指定数量的字符。 |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

读取输入流并返回下一个标记。

### skip {#skip-int-}
```
public final void skip(int count)
```

从输入流中消耗并丢弃指定数量的字符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 计数 |  | 要跳过的字符数。 |
