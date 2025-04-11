---
title: PdfExtractor.GetNextPageText
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor メソッド。1ページのテキストをファイルに保存します
type: docs
weight: 180
url: /ja/net/aspose.pdf.facades/pdfextractor/getnextpagetext/
---
## GetNextPageText(string) {#getnextpagetext_1}

1ページのテキストをファイルに保存します。

```csharp
public void GetNextPageText(string outputFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFile | String | テキストを保存するファイルのパスと名前。 |

## 例

この例は、テキスト抽出シナリオにおける GetNextPageText メソッドの使用を示しています。

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

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetNextPageText(Stream) {#getnextpagetext}

1ページのテキストをストリームに保存します。

```csharp
public void GetNextPageText(Stream outputStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | テキストを保存するストリーム。 |

## 例

この例は、テキスト抽出シナリオにおける `GetNextPageText` メソッドの使用を示しています。

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

* クラス [PdfExtractor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)