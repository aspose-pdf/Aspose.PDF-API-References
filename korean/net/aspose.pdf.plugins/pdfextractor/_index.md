---
title: "PdfExtractor 클래스"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.PdfExtractor 클래스. PDF 문서 페이지에서 발생할 수 있는 텍스트, 이미지 및 기타 유형의 콘텐츠를 추출하는 기본 기능을 나타냅니다."
type: docs
weight: 9210
url: /ko/net/aspose.pdf.plugins/pdfextractor/
---
## PdfExtractor class

PDF 문서 페이지에서 발생할 수 있는 텍스트, 이미지 및 기타 유형의 콘텐츠를 추출하기 위한 기본 기능을 나타냅니다.

```csharp
public abstract class PdfExtractor : IDisposable, IPlugin
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/pdfextractor/dispose/)() | IDisposable 구현. 실제로 PdfExtractor에 필요하지 않습니다. |
| [Process](../../aspose.pdf.plugins/pdfextractor/process/)(IPluginOptions) | 지정된 매개변수로 PdfExtractor 처리를 시작합니다. |

## 비고

`[`TextExtractor`](../textextractor/)` 객체는 텍스트를 추출하는 데 사용되며, `[`ImageExtractor`](../imageextractor/)`는 이미지를 추출하는 데 사용됩니다.

## 예제

이 예제는 PDF 문서의 텍스트 내용을 추출하는 방법을 보여줍니다.

```csharp
// PDF 내용을 추출하기 위해 TextExtractor 객체를 생성합니다.
using (TextExtractor extractor = new TextExtractor())
{
    // 지시사항을 설정하기 위해 TextExtractorOptions 객체를 생성합니다.
    textExtractorOptions = new TextExtractorOptions();
    
    // 입력 파일 경로를 데이터 소스에 추가합니다.
    textExtractorOptions.AddInput(new FileDataSource(inputPath));
    
    // 추출 프로세스를 수행합니다.
    ResultContainer resultContainer = extractor.Process(textExtractorOptions);
    
    // ResultContainer 객체에서 추출된 텍스트를 가져옵니다.
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


