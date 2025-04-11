---
title: Class PdfToDocOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfToDocOptions 클래스. DocConverter 플러그인을 위한 PDF에서 DOC 변환기 옵션을 나타냅니다.
type: docs
weight: 9090
url: /ko/net/aspose.pdf.plugins/pdftodocoptions/
---
## PdfToDocOptions 클래스

[`DocConverter`](../docconverter/) 플러그인을 위한 PDF에서 DOC 변환기 옵션을 나타냅니다.

```csharp
public sealed class PdfToDocOptions : PdfConverterOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfToDocOptions](pdftodocoptions/#constructor)() | 기본 옵션으로 `PdfToDocOptions` 객체의 새 인스턴스를 초기화합니다. |
| [PdfToDocOptions](pdftodocoptions/#constructor_1)(SaveFormat, ConversionMode) | 지정된 형식과 모드에 대한 `PdfToDocOptions` 객체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [ConversionMode](../../aspose.pdf.plugins/pdftodocoptions/conversionmode/) { get; set; } | PDF 문서가 워드 프로세싱 문서로 변환되는 방식을 제어할 수 있습니다. |
| [Inputs](../../aspose.pdf.plugins/pdfconverteroptions/inputs/) { get; } | PdfConverterOptions 플러그인 데이터 컬렉션을 반환합니다. |
| override [OperationName](../../aspose.pdf.plugins/pdftodocoptions/operationname/) { get; } | 작업의 이름을 가져옵니다. |
| [Outputs](../../aspose.pdf.plugins/pdfconverteroptions/outputs/) { get; } | 저장 작업 결과를 위한 추가 대상의 컬렉션을 가져옵니다. |
| [SaveFormat](../../aspose.pdf.plugins/pdftodocoptions/saveformat/) { get; set; } | 출력 문서의 저장 형식입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfconverteroptions/addinput/)(IDataSource) | PdfConverter 플러그인 데이터 컬렉션에 새 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/pdfconverteroptions/addoutput/)(IDataSource) | PdfToXLSXConverterOptions 플러그인 데이터 컬렉션에 새 데이터 소스를 추가합니다. |

### 참조

* 클래스 [PdfConverterOptions](../pdfconverteroptions/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)