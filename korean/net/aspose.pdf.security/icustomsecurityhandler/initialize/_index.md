---
title: "ICustomSecurityHandler.Initialize"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ICustomSecurityHandler 메서드. 암호화를 위해 현재 인스턴스를 초기화할 때 호출됩니다. 암호화 시에는 전송된 ICustomSecurityHandler 속성의 데이터로 채워지며, 암호화 사전에서 문서를 열 때도 마찬가지입니다. 새 암호화 중에 이 메서드가 호출되면 UserKey와 OwnerKey는 null이 됩니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

암호화를 위해 현재 인스턴스를 초기화할 때 호출됩니다. 암호화 시에는 전송된 속성 [`ICustomSecurityHandler`](../)의 데이터로 채워지며, 암호화 사전에서 문서를 열 때도 마찬가지입니다. 새 암호화 중에 이 메서드가 호출되면 [`UserKey`](../../encryptionparameters/userkey/)와 [`OwnerKey`](../../encryptionparameters/ownerkey/)는 null이 됩니다.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 매개변수 | EncryptionParameters | 암호화 매개변수. |

### 또 보기

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


