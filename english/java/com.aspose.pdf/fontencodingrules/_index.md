---
title: HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for Java API Reference
description: This enumeration defines rules which tune encoding logic
type: docs
weight: 15
url: /java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class HtmlSaveOptions.FontEncodingRules extends System.Enum
```

This enumeration defines rules which tune encoding logic
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | Leave encoding logic "as is" - in accordance with PDF specification |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode is a special mechanism which helps to decode input codes to unicode symbols. |
### Default {#Default}
```
public static final byte Default
```


Leave encoding logic "as is" - in accordance with PDF specification

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```


ToUnicode is a special mechanism which helps to decode input codes to unicode symbols. According to specification it must be used first of all mechanisms to get unicode symbols for specific input code. But some documents has non-standard fonts and to convert these documents correctly it may be necessary to decrease ToUnicode priority and use another mechanisms to decode input codes.

