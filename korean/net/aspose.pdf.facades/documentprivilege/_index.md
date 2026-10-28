---
title: "클래스 DocumentPrivilege"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.DocumentPrivilege 클래스. Pdf 파일에 대한 권한을 나타냅니다. Refer toPdfFileSecurity. 이 클래스를 사용하는 방법은 4가지가 있습니다. 1. 미리 정의된 권한을 직접 사용합니다. 2. 미리 정의된 권한을 기반으로 특정 권한을 일부 변경합니다. 3. 미리 정의된 권한을 기반으로 특정 Adobe Professional 권한 조합을 변경합니다. 4. 방법 2와 방법 3을 혼합합니다."
type: docs
weight: 4350
url: /ko/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class

Pdf 파일에 대한 권한을 나타냅니다. Refer to[`PdfFileSecurity`](../pdffilesecurity/). 이 클래스를 사용하는 방법은 4가지가 있습니다: 1. 미리 정의된 권한을 직접 사용합니다. 2. 미리 정의된 권한을 기반으로 특정 권한을 일부 변경합니다. 3. 미리 정의된 권한을 기반으로 특정 Adobe Professional 권한 조합을 변경합니다. 4. 방법2와 방법3을 혼합합니다.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | 모두 허용됩니다. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | 파일 조립을 허용합니다. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | 파일 복사를 허용합니다. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | 품질 저하 인쇄를 허용합니다. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | 파일에서 양식 작성을 허용합니다. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | 모두 금지됩니다. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | 파일의 주석 수정을 허용합니다. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | 파일 수정을 허용합니다. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | 파일 인쇄를 허용합니다. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | 스크린에서만 읽기를 허용합니다. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | 조립을 허용할지 여부를 설정합니다. true는 허용, false는 금지입니다. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | 복사를 허용할지 여부를 설정합니다. true는 허용, false는 금지입니다. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | 품질 저하 인쇄를 허용할지 여부를 설정합니다. true는 허용, false는 금지입니다. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | 양식 작성을 허용할지 여부를 설정합니다. true는 허용, false는 금지입니다. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | 주석 수정을 허용할지 여부를 설정합니다. true는 허용, false는 금지입니다. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | 내용 수정을 허용할지 여부를 설정합니다. true는 허용, false는 금지입니다. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | 인쇄를 허용할지 여부를 설정합니다. true는 허용, false는 금지입니다. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | 스크린 리더를 허용할지 여부를 설정합니다. true는 허용, false는 금지합니다. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | 문서 권한의 변경 수준을 가져오고 설정합니다. Adobe Professional의 'Changes Allowed' 설정과 동일합니다. 0: 없음. 1: 페이지 삽입, 삭제 및 회전. 2: 양식 필드 채우기 및 기존 서명 필드 서명. 3: 주석 달기, 양식 필드 채우기 및 기존 서명 필드 서명. 4: 페이지 추출을 제외한 모든 작업. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | 문서 권한의 복사 수준을 가져오고 설정합니다. Adobe Professional의 권한 설정과 동일합니다. 0: 없음. 1: 시각 장애인을 위한 화면 판독기 장치에 텍스트 접근 허용. 2: 텍스트, 이미지 및 기타 콘텐츠 복사 허용. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | 문서 권한의 인쇄 수준을 가져오고 설정합니다. Adobe Professional의 'Printing Allowed' 설정과 동일합니다. 0: 없음. 1: 저해상도 (150 dpi). 2: 고해상도. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | 두 `DocumentPrivilege` 객체를 비교합니다.  비교할 객체. 이 인스턴스와 value의 상대 값을 나타내는 부호 있는 정수입니다. 0보다 작으면 이 인스턴스가 value보다 작습니다. 0이면 이 인스턴스가 value와 같습니다. 0보다 크면 이 인스턴스가 value보다 큽니다. |

## 예제

```csharp
[C#]	
//Way1: 미리 정의된 권한을 직접 사용합니다.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: 미리 정의된 권한을 기반으로 하여 특정 권한을 변경합니다.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: 미리 정의된 권한을 기반으로 하여 특정 Adobe Professional 권한 조합을 변경합니다.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: way2와 way3을 혼합합니다.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### 또 보기

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


