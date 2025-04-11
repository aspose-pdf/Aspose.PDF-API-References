---
title: Class XForm
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XForm クラス。クラスは XForm を表します
type: docs
weight: 11330
url: /ja/net/aspose.pdf/xform/
---
## XForm クラス

クラスは XForm を表します

```csharp
public sealed class XForm : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BBox](../../aspose.pdf/xform/bbox/) { get; set; } | フォームのバウンディングボックスを取得または設定します。 |
| [Contents](../../aspose.pdf/xform/contents/) { get; } | フォームのオペレーターを取得します。 |
| [IT](../../aspose.pdf/xform/it/) { get; } | フォーム IT を取得します。フォーム IT は XObject の意図を説明する名前です。 |
| [Matrix](../../aspose.pdf/xform/matrix/) { get; set; } | フォームのマトリックスを取得または設定します。 |
| [Name](../../aspose.pdf/xform/name/) { get; set; } | フォーム名を取得または設定します。フォーム名はページリソースの XObject 辞書でフォームを参照するために使用される名前です。 |
| [Opi](../../aspose.pdf/xform/opi/) { get; } | オープン・プレプレス・インターフェース (OPI) を取得します。 |
| [Rectangle](../../aspose.pdf/xform/rectangle/) { get; } | フォームの矩形を取得または設定します。 |
| [Resources](../../aspose.pdf/xform/resources/) { get; } | フォーム XObject リソースを取得します。 |
| [Subtype](../../aspose.pdf/xform/subtype/) { get; } | フォームのサブタイプを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [CreateNewForm](../../aspose.pdf/xform/createnewform/)(Page, Document) | ページの内容を複製する XForm を作成します。 |
| [Dispose](../../aspose.pdf/xform/dispose/)() | メモリを解放します |
| [FreeMemory](../../aspose.pdf/xform/freememory/)() | キャッシュされたデータをクリアします |
| [GetResources](../../aspose.pdf/xform/getresources/#getresources)() | フォーム X-Object のリソースを返します。フォームにリソースがなく、allowCreate が true の場合、リソースは自動的にフォームのために作成されます。 |
| [GetResources](../../aspose.pdf/xform/getresources/#getresources_1)(bool) | フォーム X-Object のリソースを返します |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)