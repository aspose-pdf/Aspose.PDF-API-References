---
title: "クラス XfdfReader"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Annotations.XfdfReader クラス。XFDF 形式の読み取りを実行するクラスです。"
type: docs
weight: 2840
url: /ja/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

XFDF 形式の読み取りを行うクラスです。

```csharp
public sealed class XfdfReader
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XfdfReader](xfdfreader/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | XFDF ファイルを解析し、情報をハッシュテーブルとして返します。 |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | XFDF ファイルから注釈をインポートし、ドキュメントに配置します。 |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | XFDF ファイルからフィールド値をインポートします。 |

## 例

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### 関連項目

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


