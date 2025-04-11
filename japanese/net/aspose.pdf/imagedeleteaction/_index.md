---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction 列挙型。画像がコレクションから削除されるときに画像オブジェクトに対して実行されるアクション。画像オブジェクトが削除される場合
type: docs
weight: 5870
url: /ja/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction 列挙型

画像がコレクションから削除されるときに画像オブジェクトに対して実行されるアクション。画像オブジェクトが削除される場合

```csharp
public enum ImageDeleteAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| KeepContents | `0` | 画像はコレクションから削除されます。ページの内容が画像への参照を含む場合、それらは削除されません。ドキュメントが無効になる可能性があります。 |
| None | `1` | 画像はコレクションおよびページの内容から削除されますが、画像オブジェクトは削除されません。ファイルサイズは減少しません。 |
| ForceDelete | `2` | 画像はコレクションから削除され、画像オブジェクトはドキュメントから削除されます。同じオブジェクトへの他の参照が存在する場合、ドキュメントが破損する可能性があります。 |
| Check | `3` | 画像はコレクションから削除され、他のページから画像への他の参照がない場合にのみ画像オブジェクトが削除されます。これは ForceDelete オプションと比較してより多くの時間を要する場合があります。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)