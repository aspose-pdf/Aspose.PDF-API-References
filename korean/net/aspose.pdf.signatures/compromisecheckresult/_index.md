---
title: Class CompromiseCheckResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Signatures.CompromiseCheckResult 클래스. 문서 디지털 서명의 손상 여부를 확인하는 클래스입니다.
type: docs
weight: 10100
url: /ko/net/aspose.pdf.signatures/compromisecheckresult/
---
## CompromiseCheckResult 클래스

문서 디지털 서명의 손상 여부를 확인하는 클래스를 나타냅니다.

```csharp
public sealed class CompromiseCheckResult
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [HasCompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/hascompromisedsignatures/) { get; } | 문서에 손상된 디지털 서명이 있는지 여부를 나타냅니다. 최소한 하나의 서명이 손상된 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [SignaturesCoverage](../../aspose.pdf.signatures/compromisecheckresult/signaturescoverage/) { get; } | 문서의 디지털 서명의 범위 상태를 가져옵니다. Undefined와 같으면 서명 중 하나가 손상된 것입니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [CompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/compromisedsignatures/) | 손상된 것으로 확인된 디지털 서명의 컬렉션을 가져옵니다. 이 속성은 문서에서 감지된 모든 손상된 서명의 목록을 포함합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* 어셈블리 [Aspose.PDF](../../)