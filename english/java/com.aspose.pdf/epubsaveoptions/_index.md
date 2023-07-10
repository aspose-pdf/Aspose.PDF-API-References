---
title: EpubSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to EPUB format
type: docs
weight: 100
url: /java/com.aspose.pdf/epubsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class EpubSaveOptions extends UnifiedSaveOptions
```

Save options for export to EPUB format
## Constructors

| Constructor | Description |
| --- | --- |
| [EpubSaveOptions()](#EpubSaveOptions--) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getContentRecognitionMode()](#getContentRecognitionMode--) | When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. |
| [setContentRecognitionMode(int contentRecognitionMode)](#setContentRecognitionMode-int-) | When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. |
| [getTitle()](#getTitle--) | Gets or sets EPUB document title. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets EPUB document title. |
### EpubSaveOptions() {#EpubSaveOptions--}
```
public EpubSaveOptions()
```


Constructor

### getContentRecognitionMode() {#getContentRecognitionMode--}
```
public int getContentRecognitionMode()
```


When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content.

**Returns:**
int - RecognitionMode element
### setContentRecognitionMode(int contentRecognitionMode) {#setContentRecognitionMode-int-}
```
public void setContentRecognitionMode(int contentRecognitionMode)
```


When PDF file (that usually has fixed layout) is being converted, the conversion engine tries to perform grouping and multi-level analysis to restore the original document author's intent and produce result in flow layout. This property tunes that conversion for this or that desirable method of recognition of content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentRecognitionMode | int | RecognitionMode element |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets or sets EPUB document title.

**Returns:**
java.lang.String - String value
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Gets or sets EPUB document title.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

