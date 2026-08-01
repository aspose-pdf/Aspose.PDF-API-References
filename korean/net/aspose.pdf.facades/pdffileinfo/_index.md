---
title: "클래스 PdfFileInfo"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfFileInfo 클래스. PDF 문서의 메타 정보를 액세스하기 위한 클래스를 나타냅니다."
type: docs
weight: 4640
url: /ko/net/aspose.pdf.facades/pdffileinfo/
---
## PdfFileInfo class

PDF 문서의 메타 정보를 액세스하기 위한 클래스를 나타냅니다.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | `PdfFileInfo` 객체를 *document* 기반으로 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_6)(string, string) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(Stream, string, ICustomSecurityHandler) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |
| [PdfFileInfo](pdffileinfo/#constructor_7)(string, string, ICustomSecurityHandler) | Aspose.Pdf.Facades.PdfFileInfo 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | PDF 문서의 Author 정보를 가져오거나 설정합니다. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | PDF 문서의 CreationDate 정보를 가져오거나 설정합니다. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | PDF 문서의 Creator 정보를 가져오거나 설정합니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | 현재 입력 파일이 PDF 파일 컬렉션을 포함하는 'Portfolio' 파일인 경우 true를 반환합니다. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | 권한이나 문서 보안 속성을 수정하려면 비밀번호가 필요할 경우 true를 반환합니다. 이 속성은 `PdfFileInfo` 생성자에 유효한 비밀번호가 제공된 경우에만 읽을 수 있다는 점에 유의하십시오. PasswordType이 Inaccessible인 경우(잘못된 비밀번호가 제공된 경우) 이 속성을 읽으면 [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/)이 발생합니다. |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | 비밀번호로 보호된 pdf 문서를 열려면 비밀번호가 필요할 경우 true를 반환합니다. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | PDF 문서의 사용자 지정 정보를 가져오거나 설정합니다. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | PDF 문서가 암호화되었는지 확인합니다. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | 소스 입력이 유효한 PDF 파일인지 확인합니다. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | PDF 문서의 Keywords 정보를 가져오거나 설정합니다. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | PDF 문서의 ModDate 날짜 정보를 가져오거나 설정합니다. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | 문서 페이지 수를 가져옵니다. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | PdfFileInfo 인스턴스를 생성할 때 전달된 비밀번호 유형을 반환합니다. 가능한 값은 [`PasswordType`](./passwordtype/)을 참조하십시오. PDF 문서는 사용자(또는 열기) 비밀번호와 소유자(또는 권한, 편집) 비밀번호 모두를 사용하여 열 수 있다는 점에 유의하십시오. |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | PDF 문서의 Producer 정보를 가져옵니다. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | PDF 문서의 Subject 정보를 가져오거나 설정합니다. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | PDF 문서의 Title 정보를 가져오거나 설정합니다. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | [`IsPdfFile`](./ispdffile/) 속성을 사용하여 엄격한 검증 규칙을 적용합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Facade를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Facade를 초기화합니다. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | PDF 문서의 모든 메타 정보를 삭제합니다. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | 인스턴스를 비활성화합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | PDF 문서의 권한 설정을 가져옵니다. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | 속성 이름으로 PDF 문서의 사용자 지정 정보를 가져옵니다. 해당 이름과 일치하는 속성이 없으면 빈 문자열을 반환합니다. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | 지정된 페이지의 높이를 가져옵니다. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | 지정된 페이지의 회전을 가져옵니다. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | 지정된 페이지의 너비를 가져옵니다. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | 지정된 페이지 표시 영역의 수평 오프셋을 가져옵니다. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | 지정된 페이지 표시 영역의 수직 오프셋을 가져옵니다. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | PDF 문서의 버전 정보를 가져옵니다. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | PDF 문서를 지정된 파일에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | PDF 문서를 지정된 파일에 저장합니다. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | 업데이트된 PDF 문서를 지정된 파일에 저장합니다. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | 파일 정보를 설정하여 명시적으로 지정된 속성을 변경하고, 다른 속성은 그대로 유지합니다. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | PDF 문서의 사용자 지정 정보를 설정합니다. |

### 또 보기

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


