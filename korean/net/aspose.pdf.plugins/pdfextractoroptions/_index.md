---
title: Class PdfExtractorOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfExtractorOptions 클래스. TextExtractor 및 ImageExtractor 플러그인에 대한 옵션을 나타냅니다.
type: docs
weight: 9070
url: /ko/net/aspose.pdf.plugins/pdfextractoroptions/
---
## PdfExtractorOptions 클래스

TextExtractor 및 ImageExtractor 플러그인에 대한 옵션을 나타냅니다.

```csharp
public abstract class PdfExtractorOptions : IPluginOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | PdfExtractor 플러그인 데이터 컬렉션을 반환합니다. |
| virtual [OperationName](../../aspose.pdf.plugins/pdfextractoroptions/operationname/) { get; } | 작업 이름을 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | PdfExtractor 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |

## 비고

`PdfExtractorOptions`는 입력 PDF 문서를 나타내는 데이터(파일, 스트림)를 추가하는 기본 기능을 포함합니다. 대신 [`TextExtractorOptions`](../textextractoroptions/) 또는 ImageExtractorOptions를 생성하십시오.

### 참조

* 인터페이스 [IPluginOptions](../ipluginoptions/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)