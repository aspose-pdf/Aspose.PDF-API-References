---
title: "ICustomSecurityHandler.GetOwnerKey"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ICustomSecurityHandler 메서드. 암호화 사전의 O 필드에 기록될 비밀번호를 기반으로 인코딩된 배열을 생성합니다. 전달된 인수만을 사용해야 합니다. 사용자 비밀번호는 이 필드와 owner password를 사용하여 계산할 수 있습니다. 암호화 중에 호출되어 사전을 준비하고 채웁니다. 이 값은 CalculateEncryptionKey에서 UserKey로부터 키를 얻기 위해 사용할 수 있습니다. 문서 암호화를 호출할 때 사용자가 지정한 비밀번호가 전달됩니다. 비밀번호가 지정되지 않거나 하나만 지정될 수 있습니다."
type: docs
weight: 100
url: /ko/net/aspose.pdf.security/icustomsecurityhandler/getownerkey/
---
## ICustomSecurityHandler.GetOwnerKey method

암호화 사전의 O 필드에 기록될 비밀번호를 기반으로 인코딩된 배열을 생성합니다. 전달된 인수만을 사용해야 합니다. 사용자 비밀번호는 이 필드와 owner password를 사용하여 계산할 수 있습니다. 암호화 중에 호출되어 사전을 준비하고 채웁니다. 이 값은 [`CalculateEncryptionKey`](../calculateencryptionkey/)에서 UserKey로부터 키를 얻기 위해 사용할 수 있습니다. 문서 암호화를 호출할 때 사용자가 지정한 비밀번호가 전달됩니다. 비밀번호가 지정되지 않거나 하나만 지정될 수 있습니다.

```csharp
public byte[] GetOwnerKey(string userPassword, string ownerPassword)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |
| ownerPassword | String | 소유자 비밀번호. |

### 반환 값

소유자 키 배열.

### 또 보기

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


