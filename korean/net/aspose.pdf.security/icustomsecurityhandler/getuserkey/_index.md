---
title: "ICustomSecurityHandler.GetUserKey"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ICustomSecurityHandler 메서드. 사용자의 비밀번호를 기반으로 인코딩된 배열을 생성합니다. 이 값은 일반적으로 비밀번호가 사용자 또는 소유자에 속하는지 확인하고 암호화 키를 얻는 데 사용됩니다. 암호화 중에 이를 준비하고 암호화 사전을 채우기 위해 호출됩니다. 문서 암호화를 호출할 때 사용자 지정 비밀번호가 인수로 전달됩니다."
type: docs
weight: 110
url: /ko/net/aspose.pdf.security/icustomsecurityhandler/getuserkey/
---
## ICustomSecurityHandler.GetUserKey method

사용자 비밀번호를 기반으로 인코딩된 배열을 생성합니다. 이 값은 일반적으로 비밀번호가 사용자 또는 소유자에 속하는지 확인하고 암호화 키를 얻는 데 사용됩니다. 암호화 중에 호출되어 암호화 사전을 준비하고 채웁니다. 문서 암호화를 호출할 때 사용자 지정 비밀번호가 인수로 전달됩니다.

```csharp
public byte[] GetUserKey(string userPassword)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| userPassword | String | 사용자 비밀번호. |

### 반환 값

사용자 키 배열.

### 또 보기

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


