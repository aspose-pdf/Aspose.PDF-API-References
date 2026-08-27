---
title: "대리자 SignHash"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "문서 해시를 사용자 지정 서명하기 위한 대리자"
type: docs
weight: 5380
url: /ko/net/aspose.pdf.forms/signhash/
---
## SignHash delegate

문서 해시를 사용자 지정 서명하기 위한 대리자.

```csharp
public delegate byte[] SignHash(byte[] hash, DigestHashAlgorithm digestHashAlgorithm);
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 해시 | Byte[] | 문서의 입력 해시. |
| digestHashAlgorithm | DigestHashAlgorithm | 해시를 생성하는 데 사용되는 다이제스트 알고리즘입니다. 값은 절대 Auto와 같지 않습니다. |

### 반환 값

출력 서명.

## 비고

디지털 서명이 분리되었는지 여부와 관계없이, 해시 인수는 항상 서명될 최종 해시가 됩니다.

### 또 보기

* enum [DigestHashAlgorithm](../../aspose.pdf/digesthashalgorithm/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


