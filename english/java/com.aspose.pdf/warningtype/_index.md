---
title: WarningType
second_title: Aspose.PDF for Java API Reference
description: Enum represented warning type.
type: docs
weight: 399
url: /java/com.aspose.pdf/warningtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WarningType extends System.Enum
```

Enum represented warning type.
## Fields

| Field | Description |
| --- | --- |
| [SourceFileCorruption](#SourceFileCorruption) | The file is corrupted. |
| [DataLoss](#DataLoss) | Text/chart/image or other data is completely missing from either the document tree following load, or the created document following save. |
| [MajorFormattingLoss](#MajorFormattingLoss) | Major formatting losses compared to the original document. |
| [MinorFormattingLoss](#MinorFormattingLoss) | Minor formatting losses compared to the original document. |
| [CompatibilityIssue](#CompatibilityIssue) | Known issue that will prevent the document being opened by certain user agents, or previous versions of user agents. |
| [InvalidInputStreamType](#InvalidInputStreamType) | Invalid input stream type |
| [UnexpectedContent](#UnexpectedContent) | The file has unexpected content. |
### SourceFileCorruption {#SourceFileCorruption}
```
public static final int SourceFileCorruption
```


The file is corrupted.

### DataLoss {#DataLoss}
```
public static final int DataLoss
```


Text/chart/image or other data is completely missing from either the document tree following load, or the created document following save.

### MajorFormattingLoss {#MajorFormattingLoss}
```
public static final int MajorFormattingLoss
```


Major formatting losses compared to the original document. This is for occasions when the formatting loss is substantial but the data is still there.

### MinorFormattingLoss {#MinorFormattingLoss}
```
public static final int MinorFormattingLoss
```


Minor formatting losses compared to the original document. This is for minor losses of fidelity.

### CompatibilityIssue {#CompatibilityIssue}
```
public static final int CompatibilityIssue
```


Known issue that will prevent the document being opened by certain user agents, or previous versions of user agents.

### InvalidInputStreamType {#InvalidInputStreamType}
```
public static final int InvalidInputStreamType
```


Invalid input stream type

### UnexpectedContent {#UnexpectedContent}
```
public static final int UnexpectedContent
```


The file has unexpected content.

