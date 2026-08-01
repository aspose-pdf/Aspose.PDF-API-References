---
title: "PdfExtractor.GetNextPageText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor メソッド。1 ページのテキストをファイルに保存します。"
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

1ページ分のテキストをファイルに保存します。

```csharp
public void GetNextPageText(string outputFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFile | String | テキストを保存するファイルのパスと名前。 |

## 例

この例は、テキスト抽出シナリオにおける GetNextPageText メソッドの使用例を示しています。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    extractor.GetNextPageText(prefix + pageCount + suffix);
    pageCount++;
}
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf(TestPath + "Aspose.Pdf.Kit.Pdf")
extractor.ExtractText(Encoding.Unicode)
Dim prefix As String =  TestPath + "Aspose.Pdf.Kit" 
Dim suffix As String =  ".txt" 
Dim pageCount As Integer =  1 
While extractor.HasNextPageText()
    extractor.GetNextPageText(prefix + pageCount + suffix)
    pageCount = pageCount + 1
End While
```

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextPageText(Stream) {#getnextpagetext}

1ページ分のテキストをストリームに保存します。

```csharp
public void GetNextPageText(Stream outputStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | テキストを保存するストリーム。 |

## 例

この例は、テキスト抽出シナリオにおける `GetNextPageText` メソッドの使用例を示しています。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText(Encoding.Unicode);
String prefix = TestPath + @"Aspose.Pdf.Kit";
String suffix = ".txt";
int pageCount = 1;
while (extractor.HasNextPageText())
{
    FileStream fs = new FileStream(prefix + pageCount + suffix, FileMode.Create);
    extractor.GetNextPageText(prefix + pageCount + suffix);
    fs.Close();
    pageCount++;
}
```

### 関連項目

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


