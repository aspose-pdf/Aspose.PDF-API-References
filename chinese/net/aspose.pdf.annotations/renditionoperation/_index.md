---
title: "枚举 RenditionOperation"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.RenditionOperation 枚举。触发操作时要执行的操作"
type: docs
weight: 2540
url: /zh/net/aspose.pdf.annotations/renditionoperation/
---
## RenditionOperation enumeration

当操作被触发时要执行的操作。

```csharp
public enum RenditionOperation
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PlayStop | `0` | 如果没有与注释关联的呈现，则播放指定的呈现并将其关联到注释。如果已有呈现与注释关联，则应停止该呈现，并将新呈现关联到注释。 |
| Stop | `1` | 停止与注释关联的任何正在播放的呈现。 |
| Pause | `2` | 暂停与注释关联的任何正在播放的呈现。 |
| Resume | `3` | 恢复与注释关联的任何正在播放的呈现。 |
| PlayResume | `4` | 播放指定的呈现并将其关联到注释。如果已有呈现与注释关联，并且该呈现已暂停，则恢复该呈现。 |
| Undefined | `-1` | 未定义操作。 |

### 另请参见

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


