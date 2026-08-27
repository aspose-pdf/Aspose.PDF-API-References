---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Aspose.PDF for Java API Referansı"
description: "Akış halinde gelen RTF içeriğini token seti olarak çıkarmak için tasarlanmış sınıf."
type: docs
weight: 40
url: /tr/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Akış halinde gelen RTF içeriğini token seti olarak çıkarmak için tasarlanmış sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [readNextToken](#readNextToken--) | Girdi akışını okur ve bir sonraki token'ı döndürür. |
| [skip](#skip-int-) | Belirtilen sayıda karakteri girdi akışından tüketir ve atar. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Girdi akışını okur ve bir sonraki token'ı döndürür.

### skip {#skip-int-}
```
public final void skip(int count)
```

Belirtilen sayıda karakteri girdi akışından tüketir ve atar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sayım |  | Atlanacak karakter sayısı. |
