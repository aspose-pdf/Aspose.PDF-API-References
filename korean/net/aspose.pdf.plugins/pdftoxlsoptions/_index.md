---
title: Class PdfToXlsOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToXlsOptions 클래스. XlsConverter 플러그인을 위한 PDF에서 XLSX 변환기 옵션을 나타냅니다.
type: docs
weight: 9150
url: /ko/net/aspose.pdf.plugins/pdftoxlsoptions/
---
## PdfToXlsOptions 클래스

[`XlsConverter`](../xlsconverter/) 플러그인을 위한 PDF에서 XLSX 변환기 옵션을 나타냅니다.

```csharp
public sealed class PdfToXlsOptions : PdfConverterOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfToXlsOptions](pdftoxlsoptions/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Format](../../aspose.pdf.plugins/pdftoxlsoptions/format/) { get; set; } | 출력 형식입니다. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | PdfConverterOptions 플러그인 데이터 컬렉션을 반환합니다. |
| [InsertBlankColumnAtFirst](../../aspose.pdf.plugins/pdftoxlsoptions/insertblankcolumnatfirst/) { get; set; } | 워크시트의 첫 번째 열로 빈 열을 삽입해야 하는 경우 true로 설정합니다. 기본값은 false이며, 이는 빈 열이 삽입되지 않음을 의미합니다. |
| [MinimizeTheNumberOfWorksheets](../../aspose.pdf.plugins/pdftoxlsoptions/minimizethenumberofworksheets/) { get; set; } | 결과 워크북에서 워크시트 수를 최소화해야 하는 경우 true로 설정합니다. 기본값은 false이며, 이는 각 PDF 페이지를 개별 워크시트로 저장함을 의미합니다. |
| override [OperationName](../../aspose.pdf.plugins/pdftoxlsoptions/operationname/) { get; } | 작업의 이름을 가져옵니다. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 저장 작업 결과를 위한 추가 대상 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | PdfConverter 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | PdfToXLSXConverterOptions 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |

## 기타 멤버

| 이름 | 설명 |
| --- | --- |
| enum [ExcelFormat](../../aspose.pdf.plugins/pdftoxlsoptions.excelformat) | .xlsx, .xls/xml 또는 csv 파일 형식을 지정할 수 있습니다. 기본값은 XLSX입니다. |

### 참조

* class [PdfConverterOptions](../pdfconverteroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)