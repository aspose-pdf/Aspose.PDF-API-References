---
title: BeginUpdates
second_title: Aspose.PDF for .NET API 参考
description: 开始延迟更新如果您需要对同一工件进行多次更改以提高性能请使用此功能 通常当工件属性更改时工件运算符会随时更改这会导致每次更改工件时都会更改页面内容 为了避免这种影响将所有工件更新放在 StartUpdates/SaveUpdates 调用之间 这允许只更改一次页面内容
type: docs
weight: 230
url: /zh/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

开始延迟更新。如果您需要对同一工件进行多次更改以提高性能，请使用此功能。 通常，当工件属性更改时，工件运算符会随时更改。这会导致每次更改工件时都会更改页面内容 。为了避免这种影响，将所有工件更新放在 StartUpdates/SaveUpdates 调用之间。 这允许只更改一次页面内容。

```csharp
public void BeginUpdates()
```

### 例子

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### 也可以看看

* class [Artifact](../../artifact)
* 命名空间 [Aspose.Pdf](../../artifact)
* 部件 [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->