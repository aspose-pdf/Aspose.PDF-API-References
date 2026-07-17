---
title: EpubSaveOptions
linktitle: EpubSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to EPUB format
type: docs
weight: 1240
url: /java/com.aspose.pdf/epubsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.EpubSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.EpubSaveOptions

```
public class EpubSaveOptions extends UnifiedSaveOptions
```

Save options for export to EPUB format

## Constructors

| Constructor | Description |
| --- | --- |
| [EpubSaveOptions](#EpubSaveOptions--) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [getContentRecognitionMode](#getContentRecognitionMode--) | When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content. |
| [getTitle](#getTitle--) | Gets or sets EPUB document title. |
| [setContentRecognitionMode](#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-) | When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. |
| [setTitle](#setTitle-java.lang.String-) | Gets or sets EPUB document title. |

### EpubSaveOptions {#EpubSaveOptions--}
```
public EpubSaveOptions()
```

Constructor

### getContentRecognitionMode {#getContentRecognitionMode--}
```
public EpubSaveOptions.RecognitionMode getContentRecognitionMode()
```

When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content.

**Returns:**
RecognitionMode element @see RecognitionMode

### getTitle {#getTitle--}
```
public final String getTitle()
```

Gets or sets EPUB document title.

**Returns:**
String value

### setContentRecognitionMode {#setContentRecognitionMode-com.aspose.pdf.EpubSaveOptions.RecognitionMode-}
When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout.

### setTitle {#setTitle-java.lang.String-}
Gets or sets EPUB document title.
