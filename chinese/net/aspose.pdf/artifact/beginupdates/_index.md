---
title: "Artifact.BeginUpdates"
second_title: "Aspose.PDF for .NET API 参考"
description: "Artifact 方法。启动延迟更新。如果需要对同一工件进行多次更改以提升性能，请使用此功能。通常在更改工件属性时，工件操作符会随时被修改，这会导致每次工件更改时页面内容都被重新写入。为避免此效果，请将所有工件更新放在 StartUpdates/SaveUpdates 调用之间。这允许页面内容仅更新一次。"
type: docs
weight: 230
url: /zh/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

启动延迟更新。如果需要对同一工件进行多次更改以提高性能，请使用此功能。通常在工件属性更改时，工件操作员会随时更改。这会导致每次工件更改时页面内容都被更改。为避免此效果，请将所有工件更新放在 StartUpdates/SaveUpdates 调用之间。这允许仅更改一次页面内容。

```csharp
public void BeginUpdates()
```

## 示例

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### 另请参见

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


