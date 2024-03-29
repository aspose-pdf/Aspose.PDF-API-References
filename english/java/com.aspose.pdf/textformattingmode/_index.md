---
title: TextExtractionOptions.TextFormattingMode
second_title: Aspose.PDF for Java API Reference
description: Defines different modes which can be used while converting pdf document into text.
type: docs
weight: 10
url: /java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class TextExtractionOptions.TextFormattingMode extends System.Enum
```

Defines different modes which can be used while converting pdf document into text. See  TextDevice  class.
## Fields

| Field | Description |
| --- | --- |
| [Pure](#Pure) | Represent pdf content with a bit of formatting routines. |
| [Raw](#Raw) | Represent pdf content as is, i.e. |
| [Flatten](#Flatten) | Represent pdf content with positioning text fragments by their coordinates. |
| [MemorySaving](#MemorySaving) | Extraction with memory saving. |
### Pure {#Pure}
```
public static final int Pure
```


Represent pdf content with a bit of formatting routines.

### Raw {#Raw}
```
public static final int Raw
```


Represent pdf content as is, i.e. without formatting.

### Flatten {#Flatten}
```
public static final int Flatten
```


Represent pdf content with positioning text fragments by their coordinates. It is basically similar to "Raw" mode. But while "Raw" focuses on preserving the structure of text fragments (operators) in a document, "Flatten" focuses on keeping text in the order it is read.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```


Extraction with memory saving. It is almost same to 'Raw' mode but works slightly faster and uses less memory.

