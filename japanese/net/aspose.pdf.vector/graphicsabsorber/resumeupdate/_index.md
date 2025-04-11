---
title: GraphicsAbsorber.ResumeUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorber メソッド。パフォーマンス向上のために作成された Contents とすべての Contents の更新を再開します。参照してください。
type: docs
weight: 40
url: /ja/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate メソッド

[`Contents`](../../../aspose.pdf/page/contents/) とすべての [`Contents`](../../../aspose.pdf/xform/contents/) の更新を再開します。パフォーマンス向上のために作成されました。参照してください。

```csharp
public void ResumeUpdate()
```

## 例

```csharp
va.SuppressUpdate();
foreach (var el in graphicAbsorber.Elements)
{
    var pos = el.Position;
    el.Position = new Point(pos.X - 100, pos.Y);
}
va.ResumeUpdate();
```

### 参照

* クラス [GraphicsAbsorber](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)