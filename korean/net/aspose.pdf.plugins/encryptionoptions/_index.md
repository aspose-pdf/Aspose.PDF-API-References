---
title: "클래스 EncryptionOptions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Plugins.EncryptionOptions 클래스. Security 플러그인을 위한 암호화 옵션을 나타냅니다"
type: docs
weight: 8670
url: /ko/net/aspose.pdf.plugins/encryptionoptions/
---
## EncryptionOptions class

[`Security`](../security/) 플러그인을 위한 암호화 옵션을 나타냅니다.

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | `EncryptionOptions` 객체의 새 인스턴스를 기본 옵션으로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 작업이 완료된 후 입력 스트림을 닫습니다. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 작업이 완료된 후 출력 스트림을 닫습니다. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | 암호화 알고리즘, 자세한 내용은 [`CryptoAlgorithm`](./cryptoalgorithm/)을(를) 참조하십시오. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | 문서 권한, 자세한 내용은 [`Permissions`](../../aspose.pdf/permissions/)을(를) 참조하십시오. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | OrganizerOptions 플러그인 데이터 컬렉션을 반환합니다. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 저장 작업 결과를 위한 추가된 대상 컬렉션을 가져옵니다. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | 소유자 비밀번호. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | 사용자 비밀번호. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | PdfOrganizer 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | PdfOrganizer 플러그인 데이터 컬렉션에 새로운 데이터 소스를 추가합니다. |

### 또 보기

* class [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


