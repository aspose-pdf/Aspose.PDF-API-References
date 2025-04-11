---
title: Class TextExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractor 클래스. TextExtractor 플러그인을 나타냅니다.
type: docs
weight: 9380
url: /ko/net/aspose.pdf.plugins/textextractor/
---
## TextExtractor class

TextExtractor 플러그인을 나타냅니다.

```csharp
public class TextExtractor : PdfExtractor
```

## Constructors

| Name | Description |
| --- | --- |
| [TextExtractor](textextractor/)() | 기본 생성자입니다. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable의 구현입니다. 실제로 PdfExtractor에는 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 지정된 매개변수로 PdfExtractor 처리를 시작합니다. |

## Remarks

`TextExtractor` 객체는 PDF 문서에서 텍스트를 추출하는 데 사용됩니다.

## Examples

이 예제는 PDF 문서의 텍스트 내용을 추출하는 방법을 보여줍니다.

```csharp
// create TextExtractor object to extract text in PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### See Also

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)