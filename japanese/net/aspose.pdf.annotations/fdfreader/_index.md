---
title: "クラス FdfReader"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.FdfReader クラス。FDF 形式の読み取りを行うクラスです。"
type: docs
weight: 1790
url: /ja/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

FDF形式の読み取りを行うクラスです。

```csharp
public sealed class FdfReader
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | FDF ファイルからアノテーションをインポートし、ドキュメントに配置します。 |

## 例

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### 関連項目

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


