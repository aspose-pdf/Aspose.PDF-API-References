---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractor 클래스. PDF 문서의 페이지에서 발생할 수 있는 텍스트, 이미지 및 기타 유형의 콘텐츠를 추출하는 기본 기능을 나타냅니다.
type: docs
weight: 9060
url: /ko/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

PDF 문서의 페이지에서 발생할 수 있는 텍스트, 이미지 및 기타 유형의 콘텐츠를 추출하는 기본 기능을 나타냅니다.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable의 구현. 실제로 PdfExtractor에는 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 지정된 매개변수로 PdfExtractor 처리를 시작합니다. |

## Remarks

[`TextExtractor`](../textextractor/) 객체는 텍스트를 추출하는 데 사용되며, [`ImageExtractor`](../imageextractor/)는 이미지를 추출하는 데 사용됩니다.

## Examples

이 예제는 PDF 문서의 텍스트 콘텐츠를 추출하는 방법을 보여줍니다.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set instructions
    textExtractorOptions = new TextExtractorOptions();
    
    // add input file path to data sources
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### See Also

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)