---
title: Class TextExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TextExtractorOptions 클래스. TextExtractor 플러그인을 위한 텍스트 추출 옵션을 나타냅니다.
type: docs
weight: 9390
url: /ko/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions 클래스

TextExtractor 플러그인을 위한 텍스트 추출 옵션을 나타냅니다.

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | 'Raw' (기본값) 텍스트 형식 모드로 `TextExtractorOptions` 객체의 새 인스턴스를 초기화합니다. |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | 지정된 텍스트 형식 모드에 대해 `TextExtractorOptions` 객체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | 형식 모드를 가져옵니다. |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | PdfExtractor 플러그인 데이터 컬렉션을 반환합니다. |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | 작업의 이름을 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | PdfExtractor 플러그인 데이터 컬렉션에 새 데이터 소스를 추가합니다. |

## 기타 구성원

| 이름 | 설명 |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | PDF 문서를 텍스트로 변환할 때 사용할 수 있는 다양한 모드를 정의합니다. `TextExtractorOptions` 클래스를 참조하십시오. |

## 비고

`TextExtractorOptions` 객체는 텍스트 추출 작업을 위한 [`TextFormattingMode`](../textextractoroptions.textformattingmode/) 및 기타 옵션을 설정하는 데 사용됩니다. 또한 입력 PDF 문서를 나타내는 데이터(파일, 스트림)를 추가하는 기능을 상속합니다.

## 예제

이 예제는 PDF 문서의 텍스트 내용을 추출하는 방법을 보여줍니다.

```csharp
// create TextExtractor object to extract PDF contents
using (TextExtractor extractor = new TextExtractor())
{
    // create TextExtractorOptions object to set TextFormattingMode (Pure,  or Raw - default)
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // add input file path to data sources
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // perform extraction process
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // get the extracted text from the ResultContainer object
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 참조

* 클래스 [PdfExtractorOptions](../pdfextractoroptions/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)