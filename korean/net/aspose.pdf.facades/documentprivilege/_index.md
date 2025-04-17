---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.DocumentPrivilege 클래스. Pdf 파일에 접근하기 위한 권한을 나타냅니다. [`PdfFileSecurity`](../pdffilesecurity/)를 참조하십시오. 이 클래스를 사용하는 방법은 4가지입니다 1. 미리 정의된 권한을 직접 사용. 2. 미리 정의된 권한을 기반으로 특정 권한을 변경. 3. 미리 정의된 권한을 기반으로 특정 Adobe Professional 권한 조합을 변경. 4. 방법 2와 방법 3을 혼합.
type: docs
weight: 4230
url: /ko/net/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege 클래스

Pdf 파일에 접근하기 위한 권한을 나타냅니다. [`PdfFileSecurity`](../pdffilesecurity/)를 참조하십시오. 이 클래스를 사용하는 방법은 4가지입니다: 1. 미리 정의된 권한을 직접 사용. 2. 미리 정의된 권한을 기반으로 특정 권한을 변경. 3. 미리 정의된 권한을 기반으로 특정 Adobe Professional 권한 조합을 변경. 4. 방법 2와 방법 3을 혼합합니다.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | 모든 것이 허용됩니다. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | 파일 조립을 허용합니다. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | 파일 복사를 허용합니다. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | 저품질 인쇄를 허용합니다. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | 파일 내 양식 작성을 허용합니다. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | 모든 것이 금지됩니다. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | 파일의 주석 수정을 허용합니다. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | 파일 수정을 허용합니다. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | 파일 인쇄를 허용합니다. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | 화면에서만 읽기를 허용합니다. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | 조립을 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | 복사를 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | 저품질 인쇄를 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | 양식 작성을 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | 주석 수정을 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | 내용 수정을 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | 인쇄를 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | 화면 읽기를 허용하는 권한을 설정합니다. true는 허용, false는 금지입니다. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | 문서의 권한 변경 수준을 가져오고 설정합니다. Adobe Professional의 변경 허용 설정과 같습니다. 0: 없음. 1: 페이지 삽입, 삭제 및 회전. 2: 양식 필드 작성 및 기존 서명 필드 서명. 3: 주석 달기, 양식 필드 작성 및 기존 서명 필드 서명. 4: 페이지 추출 제외 모든 것. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | 문서의 복사 수준을 가져오고 설정합니다. Adobe Professional의 권한 설정과 같습니다. 0: 없음. 1: 시각 장애인을 위한 화면 읽기 장치에 대한 텍스트 접근 허용. 2: 텍스트, 이미지 및 기타 콘텐츠 복사 허용. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | 문서의 인쇄 수준을 가져오고 설정합니다. Adobe Professional의 인쇄 허용 설정과 같습니다. 0: 없음. 1: 저해상도 (150 dpi). 2: 고해상도. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | 두 `DocumentPrivilege` 객체를 비교합니다. 비교할 객체입니다. 이 인스턴스와 값의 상대적인 값을 나타내는 정수입니다. 0보다 작으면 이 인스턴스가 값보다 작습니다. 0이면 이 인스턴스가 값과 같습니다. 0보다 크면 이 인스턴스가 값보다 큽니다. |

## 예제

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
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

### 참조

* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)