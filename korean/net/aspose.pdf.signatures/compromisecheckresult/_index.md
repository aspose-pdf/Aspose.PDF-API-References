---
title: "클래스 CompromiseCheckResult"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Signatures.CompromiseCheckResult 클래스. 문서 디지털 서명의 손상 여부를 검사하기 위한 클래스를 나타냅니다"
type: docs
weight: 10280
url: /ko/net/aspose.pdf.signatures/compromisecheckresult/
---
## CompromiseCheckResult class

문서 디지털 서명의 손상 여부를 확인하는 클래스를 나타냅니다.

```csharp
public sealed class CompromiseCheckResult
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [HasCompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/hascompromisedsignatures/) { get; } | 문서에 손상된 디지털 서명이 있는지 여부를 나타냅니다. 하나 이상의 서명이 손상된 경우 true를 반환하고, 그렇지 않으면 false를 반환합니다. |
| [SignaturesCoverage](../../aspose.pdf.signatures/compromisecheckresult/signaturescoverage/) { get; } | Document에서 디지털 서명의 적용 범위 상태를 가져옵니다. 상태가 Undefined와 같으면 서명 중 하나가 손상된 것입니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| readonly [CompromisedSignatures](../../aspose.pdf.signatures/compromisecheckresult/compromisedsignatures/) | 손상된 것으로 식별된 디지털 서명의 컬렉션을 가져옵니다. 이 속성은 Document에서 감지된 모든 손상된 서명의 목록을 포함합니다. |

### 또 보기

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)


