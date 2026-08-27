---
title: "클래스 SubmitFormAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.SubmitFormAction 클래스. submitform 동작을 설명하는 클래스"
type: docs
weight: 2740
url: /ko/net/aspose.pdf.annotations/submitformaction/
---
## SubmitFormAction class

제출 양식 작업을 설명하는 클래스.

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
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | submit action의 flagas를 가져오거나 설정합니다 |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | 시퀀스상의 다음 작업. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | 대상 URL. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | ECMAScript 작업에 대한 문자열을 가져옵니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | 설정된 경우, 날짜를 나타내는 모든 제출된 필드 값은 표준 형식으로 변환됩니다. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | 설정된 경우, 제출된 FDF의 F 항목은 FDF가 제출되는 PDF 파일을 나타내는 임베디드 파일 스트림을 포함하는 파일 사양이어야 합니다. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | 설정된 경우, 제출된 FDF는 F 항목을 제외해야 합니다. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | 설정된 경우, 현재 사용자의 이름과 일치하는 T 항목을 가진 마크업 주석만 포함해야 합니다. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | 해제된 경우, Fields 배열은 제출에 포함할 필드를 지정합니다. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | 설정된 경우, 필드 이름과 값은 HTML Form 형식으로 제출되어야 합니다. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | 설정된 경우, 필드 이름과 값은 HTTP GET 요청을 사용하여 제출되어야 합니다. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | 설정된 경우, 제출된 FDF 파일은 기본 PDF 문서의 모든 마크업 주석을 포함해야 합니다. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | 설정된 경우, 제출된 FDF 파일은 모든 증분 업데이트의 내용을 포함해야 합니다. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | 설정된 경우, Fields 배열 및 Include/Exclude 플래그에 의해 지정된 모든 필드가 제출되어야 합니다. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | 설정된 경우, submit-form 동작을 일으킨 마우스 클릭 좌표가 폼 데이터의 일부로 전송되어야 합니다. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | 설정된 경우, 문서는 MIME 콘텐츠 유형 application/pdf를 사용하여 PDF 형식으로 제출되어야 합니다. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | 설정된 경우, 필드 이름과 값은 XFDF 형식으로 제출되어야 합니다. |

### 또 보기

* class [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


