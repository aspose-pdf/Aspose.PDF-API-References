---
title: Enum ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ConversionMode 列挙型。出力ドキュメントの変換モードを定義します
type: docs
weight: 8500
url: /ja/net/aspose.pdf.plugins/conversionmode/
---
## ConversionMode 列挙型

出力ドキュメントの変換モードを定義します。

```csharp
public enum ConversionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| TextBox | `0` | このモードは高速で、PDFファイルの元の外観を最大限に保持するのに適していますが、結果のドキュメントの編集可能性は制限される可能性があります。 |
| Flow | `1` | 完全認識モードで、エンジンはグルーピングと多層分析を行い、元のドキュメントの著者の意図を復元し、最大限に編集可能なドキュメントを生成します。欠点は、出力ドキュメントが元のPDFファイルとは異なる外観になる可能性があることです。 |
| EnhancedFlow | `2` | テーブルの認識をサポートする代替のFlowモードです。 |

### 参照

* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)