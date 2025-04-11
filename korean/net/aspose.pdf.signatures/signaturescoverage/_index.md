---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.SignaturesCoverage 열거형. 문서에서 디지털 서명이 제공하는 커버리지 수준에 대한 열거형을 나타냅니다.
type: docs
weight: 10110
url: /ko/net/aspose.pdf.signatures/signaturescoverage/
---
## SignaturesCoverage 열거형

문서에서 디지털 서명이 제공하는 커버리지 수준에 대한 열거형을 나타냅니다.

```csharp
public enum SignaturesCoverage
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Undefined | `0` | 문서에서 디지털 서명의 커버리지 상태가 정의되지 않았음을 나타냅니다. 이 값은 일반적으로 문서의 하나 이상의 서명이 손상되었거나 확인할 수 없을 때 사용되어 문서의 서명 커버리지에 대한 확정적인 평가를 방해합니다. |
| EntirelySigned | `1` | 문서가 디지털 서명으로 완전히 커버되어 있음을 나타냅니다. 이 값은 문서의 모든 필수 부분이 서명되었고 손상된 서명이 없음을 의미합니다. |
| PartiallySigned | `2` | 문서가 부분적으로 서명되었음을 나타내며, 이는 일부 내용만 디지털 서명으로 커버되어 있음을 의미합니다. 이 값은 문서의 특정 부분이 서명되지 않았거나 서명 커버리지에서 제외될 때 사용됩니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* 어셈블리 [Aspose.PDF](../../)