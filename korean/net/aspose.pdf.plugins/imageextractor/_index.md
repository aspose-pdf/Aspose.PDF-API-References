---
title: Class ImageExtractor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.ImageExtractor 클래스. ImageExtractor 플러그인을 나타냅니다.
type: docs
weight: 8890
url: /ko/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor 클래스

ImageExtractor 플러그인을 나타냅니다.

```csharp
public class ImageExtractor : PdfExtractor
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageExtractor](imageextractor/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable의 구현. 실제로 PdfExtractor에는 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 지정된 매개변수로 PdfExtractor 처리를 시작합니다. |

## 비고

`ImageExtractor` 객체는 PDF 문서에서 텍스트를 추출하는 데 사용됩니다.

## 예제

이 예제는 PDF 문서에서 이미지를 추출하는 방법을 보여줍니다.

```csharp
// create ImageExtractor object to extract images
using (ImageExtractor extractor = new ImageExtractor())
{
    // create ImageExtractorOptions
    imageExtractorOptions = new ImageExtractorOptions();
    
    // add input file path to data sources
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // get the image from the ResultContainer object
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### 참조

* 클래스 [PdfExtractor](../pdfextractor/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)