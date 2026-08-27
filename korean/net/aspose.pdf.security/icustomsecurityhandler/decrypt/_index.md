---
title: "ICustomSecurityHandler.Decrypt"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "ICustomSecurityHandler 메서드. 데이터 배열을 복호화합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf.security/icustomsecurityhandler/decrypt/
---
## ICustomSecurityHandler.Decrypt method

데이터 배열을 복호화합니다.

```csharp
public byte[] Decrypt(byte[] data, int objectNumber, int generation, byte[] key)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | Byte[] | 복호화할 데이터. |
| objectNumber | Int32 | 암호화된 데이터를 포함하는 객체의 번호. |
| generation | Int32 | 객체의 생성 번호. |
| 키 | Byte[] | CalculateEncryptionKey 메서드로 얻은 키 |

### 반환 값

복호화된 데이터.

### 또 보기

* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


