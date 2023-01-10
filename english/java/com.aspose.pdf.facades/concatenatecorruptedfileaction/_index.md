---
title: PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for Java API Reference
description: Action performed when corrupted file was met in concatenation process.
type: docs
weight: 10
url: /java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends System.Enum
```

Action performed when corrupted file was met in concatenation process.
## Fields

| Field | Description |
| --- | --- |
| [StopWithError](#StopWithError) | If corrupted file was met, then stop concatentation process and return error. |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | If corrupted file was met, then don't stop concatenation and don't process corrupted file. |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | When corrupted object is met in source document, process will not stopped and corrupted object only is ignored. |
### StopWithError {#StopWithError}
```
public static final int StopWithError
```


If corrupted file was met, then stop concatentation process and return error.

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```


If corrupted file was met, then don't stop concatenation and don't process corrupted file. List of corrupted files is accessible in Failures property.

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```


When corrupted object is met in source document, process will not stopped and corrupted object only is ignored.

