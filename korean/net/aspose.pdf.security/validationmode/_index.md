---
title: Enum ValidationMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Security.ValidationMode 열거형. PDF 서명 검증 프로세스의 검증 모드를 지정합니다.
type: docs
weight: 10060
url: /ko/net/aspose.pdf.security/validationmode/
---
## ValidationMode 열거형

PDF 서명 검증 프로세스의 검증 모드를 지정합니다.

```csharp
public enum ValidationMode
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | `0` | 검증이 수행되지 않는 모드를 나타냅니다. |
| OnlyCheck | `1` | 검증이 수행되지만 그 결과가 디지털 서명의 검증에 영향을 미치지 않는 모드를 나타냅니다. 검증 결과를 직접 확인할 수 있습니다. |
| Strict | `2` | 검증이 수행되며 그 결과가 디지털 서명의 검증에 영향을 미치는 모드를 나타냅니다. 인증서를 확인할 수 없는 경우 디지털 서명은 유효하지 않은 것으로 간주됩니다. 검증 결과를 직접 확인할 수 있습니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Security](../../aspose.pdf.security/)
* 어셈블리 [Aspose.PDF](../../)