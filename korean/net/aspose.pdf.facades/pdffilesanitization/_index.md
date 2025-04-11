---
title: Class PdfFileSanitization
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSanitization 클래스. 정리 및 복구 API를 나타냅니다. 다른 방법으로 문서를 생성/열 수 없는 경우 사용하십시오.
type: docs
weight: 4540
url: /ko/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization 클래스

정리 및 복구 API를 나타냅니다. 다른 방법으로 문서를 생성/열 수 없는 경우 사용하십시오.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | 기본 생성자입니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 문서 파사드가 작업 중인 문서를 가져옵니다. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | 파일이 저장된 후 파일에서 수행된 작업을 확인할 수 있습니다. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | 문서에 대한 새로운 xref 및 트레일러를 생성할 수 있습니다. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | PDF 데이터 이후의 데이터를 제거할 수 있습니다. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | PDF 데이터 이전의 데이터를 제거할 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | 파사드를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | 정리를 위해 Pdf 스트림을 바인딩합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | 정리를 위해 Pdf 파일을 바인딩합니다. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | 파사드를 닫습니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | 이전 xref와 트레일러를 제거하고 새로운 xref와 트레일러를 생성합니다. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | 문서를 복구합니다. 속성을 사용하여 사용자 정의할 수 있습니다. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | 결과 PDF를 스트림에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | 결과 PDF를 파일에 저장합니다. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | 마지막 %%EOF 이후의 데이터를 제거합니다. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | %PDF 이전의 데이터를 제거합니다. |

### 참조

* 클래스 [SaveableFacade](../saveablefacade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)