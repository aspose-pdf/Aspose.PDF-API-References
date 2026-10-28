---
title: "클래스 PdfFileSignature"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfFileSignature 클래스. 인증서를 사용하여 pdf 파일에 서명하는 클래스를 나타냅니다."
type: docs
weight: 4680
url: /ko/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

인증서를 사용하여 PDF 파일에 서명하는 클래스를 나타냅니다.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | PdfFileSignature 클래스의 생성자. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | 새 `PdfFileSignature` 객체를 *document*를 기반으로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 Document 파사드를 가져옵니다. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | 문서가 인증되었는지 여부를 결정하는 플래그를 가져옵니다. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | LTV 활성화 플래그를 가져옵니다. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | 서명의 그래픽 외관을 설정하거나 가져옵니다. 속성 값은 이미지 파일 이름을 나타냅니다. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | 서명의 그래픽 외관을 설정하거나 가져옵니다. 속성 값은 이미지 스트림을 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Facade를 초기화합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | 편집을 위해 Pdf 스트림을 바인딩합니다. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | 편집을 위해 Pdf 파일을 바인딩합니다. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | 이미 제시된 서명 필드에 배치된 MDP 서명을 사용하여 문서를 인증합니다. 서명하기 전에 서명 필드는 비어 있어야 하며, 즉 필드에 서명 사전이 포함되어 있지 않아야 합니다. 따라서 pdf 문서에 이미 서명 필드가 존재하므로 서명을 찍을 위치를 제공할 필요가 없으며, 해당 페이지와 사각형은 서명 이름으로 찾은 서명 필드에서 가져옵니다 (sigName 매개변수 참조). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | MDP 서명을 사용하여 문서를 인증합니다. 서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성을 통해 제공되어야 합니다. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Facade를 닫습니다. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | PDF에 디지털 서명이 있는지 확인합니다. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | PDF에 사용 권한이 있는지 확인합니다. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | 서명이 전체 문서를 포함하는지 확인합니다. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Facade를 해제합니다. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | 서명의 단일 X.509 인증서를 스트림으로 추출합니다. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | 서명의 이미지를 추출합니다. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | MDP 서명 유형에 의해 인증된 문서의 접근 권한 값을 반환합니다. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | 모든 빈 서명 필드의 이름을 가져옵니다. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | 서명의 연락처 정보를 가져옵니다. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | 서명의 날짜 및 시간을 가져옵니다. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | 서명의 위치를 가져옵니다. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | 서명의 이유를 가져옵니다. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | 서명의 개정을 가져옵니다. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | 모든 비어 있지 않은 서명의 이름을 가져옵니다. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | PDF 문서에 존재하는 모든 서명 알고리즘에 대한 정보를 검색합니다. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | PDF 문서에 서명하는 사람 또는 조직의 이름을 가져옵니다. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | 전체 개정을 가져옵니다. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | 서명 이름에 따라 서명을 제거합니다. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | 서명 이름에 따라 서명을 제거합니다. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | 모든 서명을 제거합니다. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | 사용 권한 항목을 제거합니다. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | 결과 PDF를 스트림에 저장합니다. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | 결과 PDF를 파일에 저장합니다. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | 서명 루틴을 위한 인증서 파일과 비밀번호를 설정합니다. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | 이미 제시된 서명 필드에 배치된 지정된 유형 서명으로 문서를 서명합니다. 서명 전에 서명 필드는 비어 있어야 하며, 즉 필드에 서명 사전이 포함되지 않아야 합니다. 따라서 PDF 문서에 이미 서명 필드가 존재하므로 서명을 찍을 위치, 해당 페이지 및 사각형을 제공할 필요가 없으며, 이는 서명 이름(SigName 매개변수)으로 찾은 서명 필드에서 가져옵니다. 서명 이유, 연락처 및 위치와 같은 데이터는 Signature 객체 sig의 해당 속성으로 제공되어야 합니다. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | 지정된 유형 서명으로 문서를 서명합니다. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | 이미 제시된 서명 필드에 배치된 지정된 유형 서명으로 문서를 서명합니다. 서명 전에 서명 필드는 비어 있어야 하며, 즉 필드에 서명 사전이 포함되지 않아야 합니다. 따라서 PDF 문서에 이미 서명 필드가 존재하므로 서명을 찍을 위치를 제공할 필요가 없으며, 해당 페이지와 사각형은 서명 이름(SigName 매개변수)으로 찾은 서명 필드에서 가져옵니다. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | PDF 문서에 서명을 만듭니다. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | 지정된 유형 서명으로 문서를 서명합니다. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | 이미 제시된 서명 필드에 배치된 지정된 유형 서명으로 문서를 서명합니다. 서명하기 전에 PDF 문서에 서명 필드가 이미 있어야 하며, 해당 페이지와 사각형은 서명 이름으로 찾은 서명 필드에서 가져옵니다 (SigName 매개변수 참조). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | 서명의 단일 X.509 인증서를 스트림으로 추출합니다. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | 서명의 단일 X.509 인증서를 추출합니다. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | 서명의 유효성을 검사합니다. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | 서명의 유효성을 검사합니다. 검증은 외부 공개 키 인증서를 사용하여 수행됩니다. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | 서명의 유효성을 검사합니다. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | 서명의 유효성을 검사합니다. 검증은 외부 공개 키 인증서를 사용하여 수행됩니다. |

### 또 보기

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


