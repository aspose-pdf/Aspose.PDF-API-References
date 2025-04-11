---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FdfReader クラス。FDF 形式の読み取りを行うクラス
type: docs
weight: 1700
url: /ja/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader クラス

FDF 形式の読み取りを行うクラスです。

```csharp
public sealed class FdfReader
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | FDF ファイルから注釈をインポートし、それらをドキュメントに配置します。 |

## 例

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### 参照

* 名前空間 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../)