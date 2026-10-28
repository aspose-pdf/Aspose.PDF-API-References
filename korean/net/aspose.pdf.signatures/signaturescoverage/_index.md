---
title: "Enum SignaturesCoverage"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Signatures.SignaturesCoverage 열거형. Document에서 디지털 서명이 제공하는 적용 범위 수준을 나타내는 열거형입니다."
type: docs
weight: 10290
url: /ko/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage enumeration

문서에서 디지털 서명이 제공하는 적용 범위 수준을 나타내는 열거형입니다.

```csharp
public enum SignaturesCoverage
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Undefined | `0` | Document에서 디지털 서명의 적용 범위 상태가 정의되지 않았음을 나타냅니다. 이 값은 Document의 하나 이상의 서명이 손상되었거나 확인할 수 없어 Document 서명 적용 범위에 대한 명확한 평가를 할 수 없을 때 일반적으로 사용됩니다. |
| EntirelySigned | `1` | Document가 디지털 서명으로 완전히 적용되었음을 나타냅니다. 이 값은 Document의 모든 필요한 부분이 서명되었으며 서명이 손상되지 않았음을 의미합니다. |
| PartiallySigned | `2` | Document가 부분적으로 서명되었음을 나타냅니다. 즉, 일부 내용은 디지털 서명으로 적용되었지만 전체가 아닌 경우입니다. 이 값은 Document의 특정 부분이 서명되지 않았거나 서명 적용 범위에서 제외될 때 사용됩니다. |

### 또 보기

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


