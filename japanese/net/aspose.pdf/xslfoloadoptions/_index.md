---
title: "クラス XslFoLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XslFoLoadOptions クラス。XSLFO ファイルを PDF ドキュメントにロード/インポートするためのオプションを表します"
type: docs
weight: 11720
url: /ja/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions class

XSL-FO ファイルを pdf ドキュメントにロード/インポートするオプションを表します。

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | XSL データなしで `XslFoLoadOptions` オブジェクトを作成します。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | XSL データ付きで `XslFoLoadOptions` オブジェクトを作成します。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | XSL データ付きで `XslFoLoadOptions` オブジェクトを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | ロードされた SVG ファイルで参照されている外部リソース（存在する場合）の相対パスを検索する基礎パス/URL。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML を PDF ドキュメントに変換するための XSL データを取得します。 |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | 既存の XLS パラメータに値を挿入するための XsltArgumentList。XLS ファイルに値のない 'animal' パラメータがある場合：XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); これにより、コンバータは XLS ファイルに値 'cat' の 'animal' パラメータがあるとみなします。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | ソース XSLFO ドキュメントには書式エラーが含まれる可能性があります。この列挙体はそのエラーの処理戦略を列挙します。 |

## 例

次の例は XSL-FO ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
// documents ディレクトリへのパス。
string dataDir = @"YOUR_DATA_DIRECTORY";

// XSL-FO ファイルへのパス。
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// 出力 PDF ファイルへのパス。
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// XslFoLoadOptions を初期化する	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // PDF ファイルを保存する
    pdfDocument.Save(pdfFile);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your XSL-FO File.
    Dim xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf")
 
    ' Initialize XslFoLoadOptions  
    Dim xslFoLoadOptions As XslFoLoadOptions = New XslFoLoadOptions()
 
    Using pdfDocument As Document = New Document(xslFoFile, xslFoLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### 関連項目

* class [XmlLoadOptions](../xmlloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


