---
title: Class PdfAConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConverter sınıfı. PDF belgelerinin PDF/A formatına dönüştürülmesi ve PDF/A uyumluluğunun doğrulanması için bir eklenti temsil eder.
type: docs
weight: 9000
url: /tr/net/aspose.pdf.plugins/pdfaconverter/
---
## PdfAConverter Sınıfı

PDF belgelerinin PDF/A formatına dönüştürülmesi ve PDF/A uyumluluğunun doğrulanması için bir eklenti temsil eder.

```csharp
public sealed class PdfAConverter : IPlugin
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [PdfAConverter](pdfaconverter/)() | Varsayılan yapıcı. |

## Metotlar

| İsim | Açıklama |
| --- | --- |
| [Process](../../aspose.pdf.plugins/pdfaconverter/process/)(IPluginOptions) | Verilen seçeneklerle bir PDF/A dönüştürme veya doğrulama sürecini başlatır. |

## Örnekler

Örnek, PDF belgesinin PDF/A formatına (bu durumda PDF/A-1a) uyumluluğunu nasıl doğrulayacağınızı gösterir:

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

Örnek, PDF belgesini PDF/A formatına (bu durumda PDF/A-3b) nasıl dönüştüreceğinizi gösterir:

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

### Ayrıca Bakınız

* arayüz [IPlugin](../iplugin/)
* ad alanı [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* derleme [Aspose.PDF](../../)