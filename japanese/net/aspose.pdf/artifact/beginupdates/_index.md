---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Artifact メソッド。遅延更新を開始します。この機能は、パフォーマンスを向上させるために同じアーティファクトに対して複数の変更を加える必要がある場合に使用します。通常、アーティファクトのプロパティが変更されると、アーティファクトオペレーターはいつでも変更されます。これにより、アーティファクトが変更されるたびにページの内容が変更されます。この影響を避けるために、すべてのアーティファクトの更新を StartUpdates/SaveUpdates 呼び出しの間に置いてください。これにより、ページの内容を一度だけ変更することができます。
type: docs
weight: 230
url: /ja/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates メソッド

遅延更新を開始します。この機能は、パフォーマンスを向上させるために同じアーティファクトに対して複数の変更を加える必要がある場合に使用します。通常、アーティファクトのプロパティが変更されると、アーティファクトオペレーターはいつでも変更されます。これにより、アーティファクトが変更されるたびにページの内容が変更されます。この影響を避けるために、すべてのアーティファクトの更新を StartUpdates/SaveUpdates 呼び出しの間に置いてください。これにより、ページの内容を一度だけ変更することができます。

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

### 参照

* クラス [Artifact](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)