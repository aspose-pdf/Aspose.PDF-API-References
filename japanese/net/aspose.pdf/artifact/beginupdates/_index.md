---
title: "Artifact.BeginUpdates"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Artifact メソッド。遅延更新を開始します。同じアーティファクトに対して複数の変更を行い、パフォーマンスを向上させたい場合にこの機能を使用します。通常、アーティファクトのプロパティが変更されるたびにアーティファクト演算子が変更され、アーティファクトが変更されるたびにページ内容が変更されます。この影響を回避するには、すべてのアーティファクト更新を StartUpdates/SaveUpdates 呼び出しの間に配置します。これにより、ページ内容の変更を一度だけに抑えることができます"
type: docs
weight: 230
url: /ja/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

遅延更新を開始します。同じアーティファクトに対して複数の変更を行う必要がある場合に、パフォーマンス向上のためにこの機能を使用します。通常、アーティファクトのプロパティが変更されるたびにアーティファクト演算子が変更されます。これにより、アーティファクトが変更されるたびにページの内容が変更されます。この影響を回避するには、すべてのアーティファクト更新を StartUpdates/SaveUpdates 呼び出しの間に配置します。これにより、ページの内容を一度だけ変更できます。

```csharp
public void BeginUpdates()
```

## 例

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### 関連項目

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


