---
title: GraphicsAbsorber.SuppressUpdate
second_title: Aspose.PDF for .NET API Reference
description: GraphicsAbsorberメソッド。ContentsおよびすべてのContentsの更新を抑制します。パフォーマンス向上のために作成されました。詳細については、参照してください。
type: docs
weight: 50
url: /ja/net/aspose.pdf.vector/graphicsabsorber/suppressupdate/
---
## GraphicsAbsorber.SuppressUpdateメソッド

[`Contents`](../../../aspose.pdf/page/contents/)およびすべての[`Contents`](../../../aspose.pdf/xform/contents/)の更新を抑制します。パフォーマンス向上のために作成されました。詳細については、参照してください。

```csharp
public void SuppressUpdate()
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