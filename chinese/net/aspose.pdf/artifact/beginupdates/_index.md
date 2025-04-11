---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Artifact 方法。开始延迟更新。如果您需要对同一工件进行多次更改以提高性能，请使用此功能。通常，当工件属性发生更改时，工件操作员会随时更改。这会导致每次更改工件时页面内容都会发生变化。为了避免这种效果，请将所有工件更新放在 StartUpdates/SaveUpdates 调用之间。这允许仅更改一次页面内容。
type: docs
weight: 230
url: /zh/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates 方法

开始延迟更新。如果您需要对同一工件进行多次更改以提高性能，请使用此功能。通常，当工件属性发生更改时，工件操作员会随时更改。这会导致每次更改工件时页面内容都会发生变化。为了避免这种效果，请将所有工件更新放在 StartUpdates/SaveUpdates 调用之间。这允许仅更改一次页面内容。

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

### 另请参阅

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)