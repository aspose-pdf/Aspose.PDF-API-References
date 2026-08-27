---
title: "列挙体 ImageDeleteAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.ImageDeleteAction 列挙体。画像オブジェクトがコレクションから削除されたときに実行されるアクションです。画像オブジェクトが削除された場合"
type: docs
weight: 6000
url: /ja/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

画像がコレクションから削除されたときに画像オブジェクトで実行されるアクションです。画像オブジェクトが削除された場合

```csharp
public enum ImageDeleteAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| KeepContents | `0` | 画像はコレクションから削除されます。ページ内容が画像への参照を含んでいる場合、それらは削除されません。文書が無効になる可能性があります。 |
| None | `1` | 画像はコレクションおよびページ内容から削除されますが、画像オブジェクト自体は削除されません。ファイルサイズは減少しません。 |
| ForceDelete | `2` | 画像はコレクションから削除され、画像オブジェクトはDocumentから削除されます。同じオブジェクトへの他の参照が存在する場合、Documentが破損する可能性があります。 |
| Check | `3` | 画像はコレクションから削除され、他のページから画像への参照がない場合にのみ画像オブジェクトが削除されます。ForceDelete オプションと比較すると、これにはより多くの時間がかかる場合があります。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


