---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConverter 클래스. PDF/A 형식으로 PDF 문서의 변환을 처리하고 PDF/A 적합성을 검증하는 플러그인을 나타냅니다.
type: docs
weight: 9000
url: /ko/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter 클래스

PDF/A 형식으로 PDF 문서의 변환을 처리하고 PDF/A 적합성을 검증하는 플러그인을 나타냅니다.

```csharp
public sealed class PdfAConverter : IPlugin
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | 주어진 옵션으로 PDF/A 변환 또는 검증 프로세스를 시작합니다. |

## 예제

이 예제는 PDF 문서가 PDF/A 형식(PDF/A-1a인 경우)에 적합한지 검증하는 방법을 보여줍니다:

```csharp
// Create the options class to set up the validation process
var options = new PdfAValidateOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_1A
};

// Add one or more files to be validated
options.AddInput(new FileDataSource("path_to_your_first_pdf_file.pdf")); // replace with your actual file path
options.AddInput(new FileDataSource("path_to_your_second_pdf_file.pdf"));
// add more files as needed

// Create the plugin instance
var plugin = new PdfAConverter();

// Run the validation and get results
var resultContainer = plugin.Process(options);

// Check the resultContainer.ResultCollection property for validation results for each file:
for (var i = 0; i < resultContainer.ResultCollection.Count; i++)
{
    var result = resultContainer.ResultCollection[i];
    var validationResult = (PdfAValidationResult) result.Data;
    var isValid = validationResult.IsValid; // Validation result for the i-th document
}
```

이 예제는 PDF 문서를 PDF/A 형식(PDF/A-3b인 경우)으로 변환하는 방법을 보여줍니다:

```csharp
// Create the options class to set up the conversion process
var options = new PdfAConvertOptions
{
    PdfAVersion = PdfAStandardVersion.PDF_A_3B
};

// Add the source file
options.AddInput(new FileDataSource("path_to_your_pdf_file.pdf")); // replace with your actual file path

// Add the path to save the converted file
options.AddOutput(new FileDataSource("path_to_the_converted_file.pdf"));

// Create the plugin instance
var plugin = new PdfAConverter();

// Run the conversion
plugin.Process(options);
```

### 참조

* 인터페이스 [IPlugin](../iplugin/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)