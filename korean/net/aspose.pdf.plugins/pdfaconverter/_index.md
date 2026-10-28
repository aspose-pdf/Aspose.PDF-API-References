---
title: "클래스 PdfAConverter"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.PdfAConverter 클래스. PDF 문서를 PDF/A 형식으로 변환하고 PDF/A 적합성을 검증하는 플러그인을 나타냅니다."
type: docs
weight: 9150
url: /ko/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter class

PDF 문서를 PDF/A 형식으로 변환하고 PDF/A 적합성을 검증하는 플러그인을 나타냅니다.

```csharp
public sealed class PdfAConverter : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | 기본 생성자. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | 주어진 옵션으로 PDF/A 변환 또는 검증 프로세스를 시작합니다. |

## 예제

이 예제는 PDF 문서가 PDF/A 형식(PDF/A-1a) 준수를 검증하는 방법을 보여줍니다:

```csharp
// 검증 프로세스를 설정하기 위해 옵션 클래스를 생성합니다
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// 검증할 하나 이상의 파일을 추가합니다
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// 필요에 따라 파일을 더 추가합니다

// 플러그인 인스턴스를 생성합니다
var plugin = new PdfAConverter();

// 검증을 실행하고 결과를 가져옵니다
var resultContainer = plugin.Process(options);

// 각 파일에 대한 검증 결과는 resultContainer.ResultCollection 속성을 확인하십시오:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

이 예제는 PDF 문서를 PDF/A 형식(PDF/A-3b)으로 변환하는 방법을 보여줍니다:

```csharp
// 변환 프로세스를 설정하기 위해 옵션 클래스를 생성합니다
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// 소스 파일을 추가합니다
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// 변환된 파일을 저장할 경로를 추가합니다
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// 플러그인 인스턴스를 생성합니다
var plugin = new PdfAConverter();

// 변환을 실행합니다
plugin.Process(options);
```

### 또 보기

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


