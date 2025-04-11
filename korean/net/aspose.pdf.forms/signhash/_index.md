---
title: Delegate SignHash
second_title: Aspose.PDF for .NET API Reference
description: 문서 해시를 사용자 정의 서명하기 위한 위임
type: docs
weight: 5260
url: /ko/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

문서 해시를 사용자 정의 서명하기 위한 위임.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| Parameter | Type | Description |
| --- | --- | --- |
| hash | Byte[] | 문서의 입력 해시. |
| digestHashAlgorithm | DigestHashAlgorithm | 해시를 생성하는 데 사용되는 다이제스트 알고리즘. 값은 절대 Auto와 같지 않습니다. |

### Return Value

출력 서명.

## Remarks

디지털 서명이 분리되어 있는지 여부에 관계없이, 해시 인자는 항상 서명될 최종 해시가 됩니다.

### See Also

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)