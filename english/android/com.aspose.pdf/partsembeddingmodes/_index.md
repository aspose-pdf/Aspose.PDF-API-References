---
title: HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for Java API Reference
description: This enum enumerates possible modes of embedding of files referenced in HTML It allows to control whether referenced files HTML FontsImages CSSes will be embedded into main HTML file or will be generated as apart binary entities
type: docs
weight: 23
url: /java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends System.Enum
```

This enum enumerates possible modes of embedding of files referenced in HTML It allows to control whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities
## Fields

| Field | Description |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | Enforces embed all referenced files(Css,Images,Fonts) into generated HTML markup (i.e. |
| [EmbedCssOnly](#EmbedCssOnly) | Enforces put apart all referenced files except CSS (Images and Fonts) I.e. |
| [NoEmbedding](#NoEmbedding) | Enforces put apart referenced files(Css,Images,Fonts) This approach generates set of files, but total size of output becames smaller(because no Base64 encoding of binaries is in use) Also such approach generates HTML that is sutable for wide set of browsers |
### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```


Enforces embed all referenced files(Css,Images,Fonts) into generated HTML markup (i.e. into HTML itself) This approach generates one HTML file, but total size of output becames bigger(because Base64 encoding of binaries is in use) and not all browsers (especially legacy) successfully process binaries embedded into HTML. But it allows get HTML that contains whole result, without any additional files.

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```


Enforces put apart all referenced files except CSS (Images and Fonts) I.e. CSS will be embedded into result HTML , and all other referenced files(Images and Fonts) will be processed as external parts It generates HTML that is sutable for wide set of browsers

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```


Enforces put apart referenced files(Css,Images,Fonts) This approach generates set of files, but total size of output becames smaller(because no Base64 encoding of binaries is in use) Also such approach generates HTML that is sutable for wide set of browsers

