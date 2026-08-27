---
title: "클래스 ImageExtractor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.ImageExtractor 클래스. ImageExtractor 플러그인을 나타냅니다."
type: docs
weight: 9020
url: /ko/net/aspose.pdf.plugins/imageextractor/
---
## ImageExtractor class

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
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable 구현. 실제로 PdfExtractor에 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 지정된 매개변수로 PdfExtractor 처리를 시작합니다. |

## 비고

`ImageExtractor` 객체는 PDF 문서에서 텍스트를 추출하는 데 사용됩니다.

## 예제

예제는 PDF 문서에서 이미지를 추출하는 방법을 보여줍니다.

```csharp
// 이미지를 추출하기 위해 ImageExtractor 객체를 생성합니다
using (ImageExtractor extractor = new ImageExtractor())
{
    // ImageExtractorOptions를 생성합니다
    imageExtractorOptions = new ImageExtractorOptions();
    
    // 입력 파일 경로를 데이터 소스에 추가합니다.
    imageExtractor.AddDataSource(new FileDataSource(inputPath));
    
    // 추출 프로세스를 수행합니다.
    ResultContainer resultContainer = extractor.Process(imageExtractorOptions);
    
    // ResultContainer 객체에서 이미지를 가져옵니다
    var imageExtracted = resultContainer.ResultCollection[0].ToFile();
}
```

### 또 보기

* class [PdfExtractor](../pdfextractor/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


