---
title: "ConversionMode 列挙型"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.ConversionMode 列挙型。出力 Document の変換モードを定義します"
type: docs
weight: 8630
url: /ja/net/aspose.pdf.plugins/conversionmode/
---
## ConversionMode enumeration

出力ドキュメントの変換モードを定義します。

```csharp
public enum ConversionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| TextBox | `0` | このモードは高速で、PDF ファイルの元の外観を最大限に保持するのに適していますが、生成されたドキュメントの編集可能性が制限される可能性があります。 |
| Flow | `1` | フル認識モードでは、エンジンがグルーピングと多層解析を実行し、元の Document 作成者の意図を復元して最大限に編集可能な Document を生成します。欠点は、出力 Document が元の PDF ファイルと見た目が異なる可能性があることです。 |
| EnhancedFlow | `2` | テーブルの認識をサポートする代替の Flow モードです。 |

### 関連項目

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


