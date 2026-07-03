---
title: RtfTokenizer
second_title: Aspose.PDF for Java API Reference
description: Class designed to extract streamed RTF content as set of tokens.
type: docs
weight: 40
url: /java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Class designed to extract streamed RTF content as set of tokens.

## Constructors

| Constructor | Description |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Methods

| Method | Description |
| --- | --- |
| [readNextToken](#readNextToken--) | Reads the input stream and returns the next token. |
| [skip](#skip-int-) | Consumes and discards the specified number of characters from the input stream. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Reads the input stream and returns the next token.

### skip {#skip-int-}
```
public final void skip(int count)
```

Consumes and discards the specified number of characters from the input stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| count |  | The number of characters to skip. |
