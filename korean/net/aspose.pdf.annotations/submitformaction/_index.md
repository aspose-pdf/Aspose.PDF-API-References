---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.SubmitFormAction 클래스. 제출 양식 작업을 설명하는 클래스
type: docs
weight: 2640
url: /ko/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction 클래스

제출 양식 작업을 설명하는 클래스입니다.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | SubmitFormAction 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | 제출 작업의 플래그를 가져오거나 설정합니다. |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 순서의 다음 작업입니다. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | 대상 URL입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript 작업에 대한 문자열을 가져옵니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | 설정된 경우, 제출된 필드 값이 날짜를 나타내면 표준 형식으로 변환됩니다. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | 설정된 경우, 제출된 FDF의 F 항목은 FDF가 제출되는 PDF 파일을 나타내는 포함된 파일 스트림을 포함하는 파일 사양이 됩니다. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | 설정된 경우, 제출된 FDF는 F 항목을 제외합니다. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | 설정된 경우, 현재 사용자의 이름과 일치하는 T 항목을 가진 마크업 주석만 포함됩니다. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | 설정 해제된 경우, Fields 배열은 제출에 포함할 필드를 지정합니다. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | 설정된 경우, 필드 이름과 값은 HTML 양식 형식으로 제출됩니다. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | 설정된 경우, 필드 이름과 값은 HTTP GET 요청을 사용하여 제출됩니다. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | 설정된 경우, 제출된 FDF 파일은 기본 PDF 문서의 모든 마크업 주석을 포함합니다. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | 설정된 경우, 제출된 FDF 파일은 모든 증분 업데이트의 내용을 포함합니다. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | 설정된 경우, Fields 배열과 Include/Exclude 플래그로 지정된 모든 필드가 제출됩니다. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | 설정된 경우, 제출 양식 작업을 유발한 마우스 클릭의 좌표가 양식 데이터의 일부로 전송됩니다. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | 설정된 경우, 문서는 MIME 콘텐츠 유형 application/pdf를 사용하여 PDF로 제출됩니다. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | 설정된 경우, 필드 이름과 값은 XFDF로 제출됩니다. |

### 참조

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)