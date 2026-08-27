---
title: "ICustomSecurityHandler.CalculateEncryptionKey"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ICustomSecurityHandler 메서드. EncryptionKey를 계산합니다. 일반적으로 키는 UserKey를 기반으로 계산됩니다. 호출 시점의 현재 매개변수를 포함하는 EncryptionParams의 값을 사용할 수 있습니다. 이 값은 Encrypt 및 Decrypt의 key 인수로 전달됩니다."
type: docs
weight: 60
url: /ko/net/aspose.pdf.security/icustomsecurityhandler/calculateencryptionkey/
---
## ICustomSecurityHandler.CalculateEncryptionKey method

EncryptionKey를 계산합니다. 일반적으로 키는 UserKey를 기반으로 계산됩니다. 호출 시점의 현재 매개변수를 포함하는 EncryptionParams의 값을 사용할 수 있습니다. 이 값은 [`Encrypt`](../encrypt/) 및 [`Decrypt`](../decrypt/)의 key 인수로 전달됩니다.

```csharp
public byte[] CalculateEncryptionKey(string password)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| password | String | 사용자가 입력한 비밀번호. |

### 반환 값

암호화 키 배열.

### 또 보기

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


