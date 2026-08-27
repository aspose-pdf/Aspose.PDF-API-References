---
title: "ICustomSecurityHandler.EncryptPermissions"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ICustomSecurityHandler 메서드. 문서의 권한 필드를 암호화합니다. 결과는 Perms 암호화 사전 필드에 기록됩니다. 문서를 열 때 해당 값은 EncryptionParameters의 Perms 필드를 통해 얻을 수 있습니다. 문서 권한이 변경되었는지 확인할 수 있습니다."
type: docs
weight: 90
url: /ko/net/aspose.pdf.security/icustomsecurityhandler/encryptpermissions/
---
## ICustomSecurityHandler.EncryptPermissions method

문서의 권한 필드를 암호화합니다. 결과는 Perms 암호화 사전 필드에 기록됩니다. 문서를 열 때 해당 값은 [`EncryptionParameters`](../../encryptionparameters/)의 Perms 필드를 통해 얻을 수 있습니다. 문서 권한이 변경되었는지 확인할 수 있습니다.

```csharp
public byte[] EncryptPermissions(int permissions)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 권한 | Int32 | 정수 형태로 표현된 문서 권한. |

### 반환 값

암호화된 배열입니다.

### 또 보기

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


