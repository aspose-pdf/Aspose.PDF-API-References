---
title: "PdfExtractor.ExtractText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfExtractor メソッド。Unicode エンコーディングを使用して Pdf ドキュメントからテキストを抽出します。"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/pdfextractor/extracttext/
---
## ExtractText() {#extracttext}

Unicodeエンコーディングを使用してPdfドキュメントからテキストを抽出します。

```csharp
public void ExtractText()
```

## 例

最初の例では、PDFファイルからすべてのテキストを抽出する方法を示します。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText();
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText()
extractor.GetText("D:\Text\text.txt")
```

2 番目の例では、各ページのテキストを 1 つの txt ファイルに抽出する方法を示します。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf");
extractor.ExtractText();
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
extractor.ExtractText()
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

## ExtractText(Encoding) {#extracttext_1}

指定されたエンコーディングを使用してPdfドキュメントからテキストを抽出します。

```csharp
public void ExtractText(Encoding encoding)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| encoding | エンコーディング | 抽出されたテキストのエンコーディングです。 |

## 例

最初の例では、PDFファイルからすべてのテキストを抽出する方法を示します。

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(@"D:\Text\text.pdf");
extractor.ExtractText(Encoding.Unicode);
extractor.GetText(@"D:\Text\text.txt");
```

```csharp
Dim extractor As PdfExtractor =  New PdfExtractor() 
extractor.BindPdf("D:\Text\text.pdf")
extractor.ExtractText(Encoding.Unicode)
extractor.GetText("D:\Text\text.txt")
```

2 番目の例では、各ページのテキストを 1 つの txt ファイルに抽出する方法を示します。

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


