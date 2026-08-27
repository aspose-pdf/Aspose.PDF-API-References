---
title: "Document.IgnoreCorruptedObjects"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document プロパティ。 ソースファイルのエラーを無視するフラグを取得または設定します。このフラグが false の場合、ソースドキュメントからページを宛先ドキュメントにコピーする際に、ソースファイル内のオブジェクトが破損していると例外でコピー処理が停止します（例: dest.Pages.Addsrc.Pages）。このフラグが true に設定されていると、破損したオブジェクトは空の値に置き換えられます。デフォルトは true です。"
type: docs
weight: 290
url: /ja/net/aspose.pdf/document/ignorecorruptedobjects/
---
## Document.IgnoreCorruptedObjects property

ソースファイルのエラーを無視するかどうかを示すフラグを取得または設定します。ソース Document から Page を宛先 Document にコピーする際、フラグが false の場合、ソースファイル内のオブジェクトが破損していると例外でコピー処理が中止されます。例: dest.Pages.Add(src.Pages); フラグが true に設定されていると、破損したオブジェクトは空の値で置き換えられます。既定は true です。

```csharp
public bool IgnoreCorruptedObjects { get; set; }
```

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


