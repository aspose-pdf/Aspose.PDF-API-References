---
title: SignaturesCompromiseDetector.Check
second_title: Aspose.PDF for .NET API Reference
description: SignaturesCompromiseDetector 메서드. 문서의 디지털 서명이 손상되었는지 확인합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf/signaturescompromisedetector/check/
---
## SignaturesCompromiseDetector.Check 메서드

문서의 디지털 서명이 손상되었는지 확인합니다.

```csharp
public bool Check(out CompromiseCheckResult compromiseCheckResult)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| compromiseCheckResult | CompromiseCheckResult& | 문서 검증 결과입니다. |

### 반환 값

서명이 손상되지 않은 경우 True입니다.

## 비고

디지털 서명이 없는 문서에 대해 이 메서드를 사용하면 `True`를 반환합니다.

### 참조

* 클래스 [CompromiseCheckResult](../../../aspose.pdf.signatures/compromisecheckresult/)
* 클래스 [SignaturesCompromiseDetector](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)