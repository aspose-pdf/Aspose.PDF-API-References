---
title: Enum RenditionOperation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RenditionOperation enum. The operation to perform when the action is triggered
type: docs
weight: 1040
url: /net/aspose.pdf.annotations/renditionoperation/
---
## RenditionOperation enumeration

The operation to perform when the action is triggered.

```csharp
public enum RenditionOperation
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| PlayStop | `0` | If no rendition is associated with the annotation, play the specified rendition, associating it with the annotation. If a rendition is already associated with the annotation, it shall be stopped, and the new rendition shall be associated with the annotation. |
| Stop | `1` | Stop any rendition being played in association with the annotation. |
| Pause | `2` | Pause any rendition being played in association with the annotation. |
| Resume | `3` | Resume any rendition being played in association with the annotation. |
| PlayResume | `4` | Play the specified rendition, associating it with the annotation. If a rendition is already associated with the annotation, resume the rendition if it is paused. |
| Undefined | `-1` | Operation not defined. |

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


