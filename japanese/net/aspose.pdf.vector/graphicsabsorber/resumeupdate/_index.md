---
title: "GraphicsAbsorber.ResumeUpdate"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "GraphicsAbsorber メソッド。Contents とすべての Contents の更新を再開します。パフォーマンス向上のために作成されました。詳細は参照してください。"
type: docs
weight: 40
url: /ja/net/aspose.pdf.vector/graphicsabsorber/resumeupdate/
---
## GraphicsAbsorber.ResumeUpdate method

[`Contents`](../../../aspose.pdf/page/contents/) とすべての [`Contents`](../../../aspose.pdf/xform/contents/) の更新を再開します。パフォーマンス向上のために作成されました。詳細は参照してください。

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

### 関連項目

* class [GraphicsAbsorber](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


