---
title: EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for Java API Reference
description: When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document.
type: docs
weight: 1250
url: /java/com.aspose.pdf/epubsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < EpubSaveOptions.RecognitionMode > com.aspose.pdf.EpubSaveOptions.RecognitionMode, java.lang.Enum < EpubSaveOptions.RecognitionMode >, com.aspose.pdf.EpubSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < EpubSaveOptions.RecognitionMode >

```
public static enum EpubSaveOptions.RecognitionMode extends Enum < EpubSaveOptions.RecognitionMode >
```

When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content.

## Fields

| Field | Description |
| --- | --- |
| [Fixed](#Fixed) | This mode is fast and good for maximally preserving the original look pages, but unfortunately many EPUB readeres don't support xhtml with fixed layout |
| [Flow](#Flow) | Full recognition mode, the engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce xhtml in flow layout. |
| [PdfFlow](#PdfFlow) | The main idea of this conversion is based on saving "natural" order of content rendering that is formed during processing of pdf documents. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### Fixed {#Fixed}
```
public static final EpubSaveOptions.RecognitionMode Fixed
```

This mode is fast and good for maximally preserving the original look pages, but unfortunately many EPUB readeres don't support xhtml with fixed layout

### Flow {#Flow}
```
public static final EpubSaveOptions.RecognitionMode Flow
```

Full recognition mode, the engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce xhtml in flow layout.

### PdfFlow {#PdfFlow}
```
public static final EpubSaveOptions.RecognitionMode PdfFlow
```

The main idea of this conversion is based on saving "natural" order of content rendering that is formed during processing of pdf documents.

### getByValue {#getByValue-int-}
```
public static EpubSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static EpubSaveOptions.RecognitionMode [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
