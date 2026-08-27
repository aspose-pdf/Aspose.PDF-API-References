---
title: "列挙型 HtmlSaveOptions.FontEncodingRules"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptionsFontEncodingRules 列挙型。 この列挙体はエンコーディングロジックを調整するルールを定義します"
type: docs
weight: 5750
url: /ja/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

この列挙体はエンコーディングロジックを調整するルールを定義します

```csharp
public enum FontEncodingRules : byte
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | `0` | エンコーディングロジックを "as is" のままにする - PDF 仕様に従って |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode は、入力コードを Unicode 記号にデコードするのに役立つ特別なメカニズムです。仕様によれば、特定の入力コードに対して Unicode 記号を取得するために、すべてのメカニズムの中で最初に使用しなければなりません。しかし、一部の文書は非標準フォントを使用しており、これらの文書を正しく変換するには ToUnicode の優先度を下げ、別のメカニズムで入力コードをデコードする必要がある場合があります。 |

### 関連項目

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


