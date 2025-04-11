---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileInfo 클래스. PDF 문서의 메타 정보를 접근하기 위한 클래스입니다.
type: docs
weight: 4520
url: /ko/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo 클래스

PDF 문서의 메타 정보를 접근하기 위한 클래스를 나타냅니다.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | 기본값으로 Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | *document*를 기반으로 새로운 `PdfFileInfo` 객체를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | PDF 문서의 저자 정보를 가져오거나 설정합니다. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | PDF 문서의 생성 날짜 정보를 가져오거나 설정합니다. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | PDF 문서의 작성자 정보를 가져오거나 설정합니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서의 파사드를 가져옵니다. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | 현재 입력 파일이 PDF 파일 모음을 포함하는 '포트폴리오' 파일인 경우 true를 반환합니다. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | 권한 또는 문서 보안 속성을 수정하는 데 비밀번호가 필요한 경우 true를 반환합니다. 이 속성은 `PdfFileInfo` 생성자에 유효한 비밀번호가 제공된 경우에만 읽을 수 있습니다. PasswordType이 Inaccessible인 경우(즉, 잘못된 비밀번호가 제공된 경우) 이 속성을 읽으면 [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/)이 발생합니다. |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | 비밀번호로 보호된 PDF 문서를 열기 위해 비밀번호가 필요한 경우 true를 반환합니다. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | PDF 문서의 사용자 정의 정보를 가져오거나 설정합니다. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | PDF 문서가 암호화되어 있는지 확인합니다. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | 소스 입력이 유효한 PDF 파일인지 확인합니다. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | PDF 문서의 키워드 정보를 가져오거나 설정합니다. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | PDF 문서의 수정 날짜 정보를 가져오거나 설정합니다. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | 문서 페이지 수를 가져옵니다. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | PdfFileInfo 인스턴스를 생성하는 데 사용된 비밀번호 유형을 반환합니다. [`PasswordType`](./passwordtype/)에서 가능한 값을 참조하십시오. PDF 문서는 사용자(또는 열기) 비밀번호와 소유자(또는 권한, 수정) 비밀번호 모두를 사용하여 열 수 있습니다. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | PDF 문서의 제작자 정보를 가져옵니다. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | PDF 문서의 주제 정보를 가져오거나 설정합니다. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | PDF 문서의 제목 정보를 가져오거나 설정합니다. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | [`IsPdfFile`](./ispdffile/) 속성을 사용하여 엄격한 검증 규칙을 사용합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 파사드를 초기화합니다. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | PDF 문서의 모든 메타 정보를 지웁니다. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | 인스턴스를 비초기화합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | PDF 문서의 권한 설정을 가져옵니다. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | 속성 이름으로 PDF 문서의 사용자 정의 정보를 가져옵니다. 이름과 일치하는 속성이 없으면 빈 문자열을 반환합니다. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | 지정된 페이지의 높이를 가져옵니다. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | 지정된 페이지의 회전을 가져옵니다. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | 지정된 페이지의 너비를 가져옵니다. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | 지정된 페이지 표시 영역의 수평 오프셋을 가져옵니다. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | 지정된 페이지 표시 영역의 수직 오프셋을 가져옵니다. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | PDF 문서의 버전 정보를 가져옵니다. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | PDF 문서를 지정된 파일에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | PDF 문서를 지정된 파일에 저장합니다. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | 업데이트된 PDF 문서를 지정된 파일에 저장합니다. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | 파일 정보를 설정하여 명시적으로 지정된 속성을 변경하고 다른 속성은 그대로 유지합니다. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | PDF 문서의 사용자 정의 정보를 설정합니다. |

### 참조

* 클래스 [SaveableFacade](../saveablefacade/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)