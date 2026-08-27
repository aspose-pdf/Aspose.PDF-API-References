---
title: "인터페이스 ICustomSecurityHandler"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Security.ICustomSecurityHandler 인터페이스. 사용자 정의 보안 처리기 인터페이스입니다."
type: docs
weight: 10150
url: /ko/net/aspose.pdf.security/icustomsecurityhandler/
---
## ICustomSecurityHandler interface

맞춤형 보안 핸들러 인터페이스입니다.

```csharp
public interface ICustomSecurityHandler
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Filter](../../aspose.pdf.security/icustomsecurityhandler/filter/) { get; } | 필터 이름을 가져옵니다. |
| [KeyLength](../../aspose.pdf.security/icustomsecurityhandler/keylength/) { get; } | 키 길이를 가져옵니다. |
| [Revision](../../aspose.pdf.security/icustomsecurityhandler/revision/) { get; } | 핸들러 또는 암호화 알고리즘 버전을 가져옵니다. |
| [SubFilter](../../aspose.pdf.security/icustomsecurityhandler/subfilter/) { get; } | 서브 필터 이름을 가져옵니다. |
| [Version](../../aspose.pdf.security/icustomsecurityhandler/version/) { get; } | 핸들러 또는 암호화 알고리즘 버전을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [CalculateEncryptionKey](../../aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/)(string) | EncryptionKey를 계산합니다. 일반적으로 키는 UserKey를 기반으로 계산됩니다. 호출 시점의 현재 매개변수를 포함하는 EncryptionParams의 값을 사용할 수 있습니다. 이 값은 [`Encrypt`](./encrypt/) 및 [`Decrypt`](./decrypt/)에서 key 인수로 전달됩니다. |
| [Decrypt](../../aspose.pdf.security/icustomsecurityhandler/decrypt/)(byte[], int, int, byte[]) | 데이터 배열을 복호화합니다. |
| [Encrypt](../../aspose.pdf.security/icustomsecurityhandler/encrypt/)(byte[], int, int, byte[]) | 데이터 배열을 암호화합니다. |
| [EncryptPermissions](../../aspose.pdf.security/icustomsecurityhandler/encryptpermissions/)(int) | 문서의 permissions 필드를 암호화합니다. 결과는 Perms 암호화 사전 필드에 기록됩니다. 문서를 열 때, 해당 값은 [`EncryptionParameters`](../encryptionparameters/)에서 Perms 필드를 통해 얻을 수 있습니다. 이를 통해 문서 권한이 변경되었는지 확인할 수 있습니다. |
| [GetOwnerKey](../../aspose.pdf.security/icustomsecurityhandler/getownerkey/)(string, string) | 암호화 사전의 O 필드에 기록될 비밀번호를 기반으로 인코딩된 배열을 생성합니다. 전달된 인수만을 사용해야 합니다. 사용자 비밀번호는 소유자 비밀번호를 사용하여 이 필드에서 계산될 수 있습니다. 암호화 중에 호출되어 암호화 사전을 준비하고 채웁니다. 해당 값은 [`CalculateEncryptionKey`](./calculateencryptionkey/)에서 UserKey로부터 키를 얻기 위해 사용 가능합니다. 문서 암호화를 호출할 때 사용자가 지정한 비밀번호가 전달됩니다. 비밀번호가 지정되지 않거나 하나만 지정될 수 있습니다. |
| [GetUserKey](../../aspose.pdf.security/icustomsecurityhandler/getuserkey/)(string) | 사용자 비밀번호를 기반으로 인코딩된 배열을 생성합니다. 이 값은 일반적으로 비밀번호가 사용자 또는 소유자에 속하는지 확인하고 암호화 키를 얻는 데 사용됩니다. 암호화 중에 호출되어 암호화 사전을 준비하고 채웁니다. 문서 암호화를 호출할 때 사용자 지정 비밀번호가 인수로 전달됩니다. |
| [Initialize](../../aspose.pdf.security/icustomsecurityhandler/initialize/)(EncryptionParameters) | 암호화를 위해 현재 인스턴스를 초기화할 때 호출됩니다. 암호화 시에는 전송된 속성 `ICustomSecurityHandler`의 데이터로 채워지며, 암호화 사전에서 문서를 열 때도 채워집니다. 새 암호화 중에 메서드가 호출되면 [`UserKey`](../encryptionparameters/userkey/) 및 [`OwnerKey`](../encryptionparameters/ownerkey/)가 null이 됩니다. |
| [IsOwnerPassword](../../aspose.pdf.security/icustomsecurityhandler/isownerpassword/)(string) | 비밀번호가 문서 소유자 비밀번호인지 확인합니다. 이 메서드는 Initialize 후에 호출됩니다. 해당 메서드 호출은 PDF API에서 사용됩니다. |
| [IsUserPassword](../../aspose.pdf.security/icustomsecurityhandler/isuserpassword/)(string) | 비밀번호가 사용자(문서를 여는 비밀번호)에 속하는지 확인합니다. 이 메서드는 Initialize 후에 호출됩니다. 해당 메서드 호출은 PDF API에서 사용됩니다. |

### 또 보기

* namespace [Aspose.Pdf.Security](../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../)


