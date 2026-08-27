---
title: "클래스 PdfFileSanitization"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfFileSanitization 클래스. 정화 및 복구 API를 나타냅니다. 다른 방법으로 문서를 생성/열 수 없을 때 사용하십시오."
type: docs
weight: 4660
url: /ko/net/aspose.pdf.facades/pdffilesanitization/
---
## PdfFileSanitization class

정화 및 복구 API를 나타냅니다. 다른 방법으로 문서를 생성/열 수 없을 때 사용하십시오.

```csharp
public sealed class PdfFileSanitization : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileSanitization](pdffilesanitization/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |
| [Log](../../aspose.pdf.facades/pdffilesanitization/log/) { get; } | 파일이 저장된 후 파일에 대해 수행된 작업을 확인할 수 있습니다. |
| [UseRebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/userebuildxrefandtrailer/) { get; set; } | 문서에 대한 새로운 xref와 트레일러를 생성할 수 있습니다. |
| [UseTrimBottom](../../aspose.pdf.facades/pdffilesanitization/usetrimbottom/) { get; set; } | PDF 데이터 이후의 데이터를 제거할 수 있습니다. |
| [UseTrimTop](../../aspose.pdf.facades/pdffilesanitization/usetrimtop/) { get; set; } | PDF 데이터 이전의 데이터를 제거할 수 있습니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf)(Document) | Facade를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_1)(Stream) | 정화를 위해 Pdf 스트림을 바인딩합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesanitization/bindpdf/#bindpdf_2)(string) | Sanitize를 위해 Pdf 파일을 바인드합니다. |
| override [Close](../../aspose.pdf.facades/pdffilesanitization/close/)() | Facade를 닫습니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| [RebuildXrefAndTrailer](../../aspose.pdf.facades/pdffilesanitization/rebuildxrefandtrailer/)() | 트레일러와 함께 기존 xref를 제거하고 새 트레일러가 있는 xref를 생성합니다. |
| [Recover](../../aspose.pdf.facades/pdffilesanitization/recover/)() | 문서를 복구합니다. 속성을 사용하여 사용자 지정하십시오. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save)(Stream) | 결과 PDF를 스트림에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdffilesanitization/save/#save_1)(string) | 결과 PDF를 파일에 저장합니다. |
| [TrimBottom](../../aspose.pdf.facades/pdffilesanitization/trimbottom/)() | 마지막 %%EOF 이후의 데이터를 제거합니다. |
| [TrimTop](../../aspose.pdf.facades/pdffilesanitization/trimtop/)() | %PDF 이전의 데이터를 제거합니다. |

### 또 보기

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


