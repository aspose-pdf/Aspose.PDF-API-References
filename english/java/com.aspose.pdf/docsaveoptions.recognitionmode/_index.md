---
title: DocSaveOptions.RecognitionMode
linktitle: DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for Java API Reference
description: Allows to control how a PDF document is converted into a word processing document. Use the RecognitionMode.Textbox mode when the resulting document is not goining to be heavily.
type: docs
weight: 1050
url: /java/com.aspose.pdf/docsaveoptions.recognitionmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < DocSaveOptions.RecognitionMode > com.aspose.pdf.DocSaveOptions.RecognitionMode, java.lang.Enum < DocSaveOptions.RecognitionMode >, com.aspose.pdf.DocSaveOptions.RecognitionMode

**All Implemented Interfaces:**
Serializable, Comparable < DocSaveOptions.RecognitionMode >

```
public static enum DocSaveOptions.RecognitionMode extends Enum < DocSaveOptions.RecognitionMode >
```

Allows to control how a PDF document is converted into a word processing document. Use the RecognitionMode.Textbox mode when the resulting document is not goining to be heavily edited futher. Textboxes are easy to modify when there is not a lot to do. Use the RecognitionMode.Flow mode when the output document needs further editing. Paragraphs and texlines in the flow mode allow easy modification of text, but unupported formatting objects will look worse than in the RecognitionMode.Textbox mode.

## Fields

| Field | Description |
| --- | --- |
| [EnhancedFlow](#EnhancedFlow) | An alternative Flow mode that supports the recognition of tables. |
| [Flow](#Flow) | Full recognition mode, the engine performs grouping and multi-level analysis to restore the original document author's intent and produce a maximally editable document. |
| [Textbox](#Textbox) | This mode is fast and good for maximally preserving original look of the PDF file, but editability of the resulting document could be limited. |

## Methods

| Method | Description |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Returns the enum constant of this type with the specified name. |
| [values](#values--) | Returns an array containing the constants of this enum type, in the order they are declared. |

### EnhancedFlow {#EnhancedFlow}
```
public static final DocSaveOptions.RecognitionMode EnhancedFlow
```

An alternative Flow mode that supports the recognition of tables.

### Flow {#Flow}
```
public static final DocSaveOptions.RecognitionMode Flow
```

Full recognition mode, the engine performs grouping and multi-level analysis to restore the original document author's intent and produce a maximally editable document.

### Textbox {#Textbox}
```
public static final DocSaveOptions.RecognitionMode Textbox
```

This mode is fast and good for maximally preserving original look of the PDF file, but editability of the resulting document could be limited.

### getByValue {#getByValue-int-}
```
public static DocSaveOptions.RecognitionMode getByValue(int value)
```



### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Returns the enum constant of this type with the specified name.

### values {#values--}
```
public static DocSaveOptions.RecognitionMode [] values()
```

Returns an array containing the constants of this enum type, in the order they are declared.

**Returns:**
an array containing the constants of this enum type, in the order they are declared
