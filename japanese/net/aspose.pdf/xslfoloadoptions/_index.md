---
title: Class XslFoLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptions クラス。PDF ドキュメントに XSLFO ファイルを読み込む/インポートするためのオプションを表します。
type: docs
weight: 11530
url: /ja/net/aspose.pdf/xslfoloadoptions/
---
## XslFoLoadOptions クラス

PDF ドキュメントに XSL-FO ファイルを読み込む/インポートするためのオプションを表します。

```csharp
public sealed class XslFoLoadOptions : XmlLoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XslFoLoadOptions](xslfoloadoptions/#constructor)() | XSL データなしで `XslFoLoadOptions` オブジェクトを作成します。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_1)(Stream) | XSL データを持つ `XslFoLoadOptions` オブジェクトを作成します。 |
| [XslFoLoadOptions](xslfoloadoptions/#constructor_2)(string) | XSL データを持つ `XslFoLoadOptions` オブジェクトを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BasePath](../../aspose.pdf/xslfoloadoptions/basepath/) { get; set; } | 読み込まれた SVG ファイルで参照される外部リソースへの相対パスを検索するためのベースパス/URL。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスによって禁止されているフォントでの操作を実行できるようにします。たとえば、このフォントの埋め込みを無効にするライセンスルールがある場合でも、PDF ドキュメントにフォントを埋め込むことを許可します。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型の項目を返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は停止する必要があります。 |
| [XslStream](../../aspose.pdf/xmlloadoptions/xslstream/) { get; } | XML を PDF ドキュメントに変換するための XSL データを取得します。 |
| [XsltArgumentList](../../aspose.pdf/xslfoloadoptions/xsltargumentlist/) { get; set; } | 既存の XLS パラメータに値を挿入するための XsltArgumentList。XLS ファイルには値のない 'animal' パラメータがあります: XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); これにより、変換器は XLS ファイルに 'cat' という値の 'animal' パラメータがあると仮定します。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ParsingErrorsHandlingType](../../aspose.pdf/xslfoloadoptions/parsingerrorshandlingtype/) | ソース XSLFO ドキュメントにはフォーマットエラーが含まれている可能性があります。この列挙型は、そのエラーの処理に関する可能な戦略を列挙します。 |

## 例

次の例は、XSL-FO ファイルを PDF ファイルに変換する方法を示しています。

```csharp
[C#]
// The path to the documents directory.
string dataDir = @"YOUR_DATA_DIRECTORY";

// The path to your XSL-FO File.
string xslFoFile = Path.Combine(dataDir, "XSLFO-to-PDF.xslfo");

// The path to output PDF File.
string pdfFile = Path.Combine(dataDir, "XSLFO-to-PDF.pdf");

// Initialize XslFoLoadOptions	
XslFoLoadOptions xslFoLoadOptions = new XslFoLoadOptions();
    
using (Document pdfDocument = new Document(xslFoFile, xslFoLoadOptions))
{
 
    // Save PDF file
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

### 参照

* クラス [XmlLoadOptions](../xmlloadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)