---
title: "열거형 KeySize"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.KeySize 열거형. PDF 문서를 암호화하는 데 사용할 수 있는 다양한 키 크기를 정의합니다."
type: docs
weight: 4510
url: /ko/net/aspose.pdf.facades/keysize/
---
## KeySize enumeration

pdf 문서를 암호화하는 데 사용할 수 있는 다양한 키 크기를 정의합니다.

```csharp
public enum KeySize
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| x40 | `0` | 40비트 키. 이러한 키 크기는 RC4 알고리즘과 함께 사용되며 낮은 수준의 보안을 제공합니다. 그러나 PDF 문서의 이전 버전은 이러한 키(버전 1.3 이하)만으로 암호화될 수 있습니다; |
| x128 | `1` | 128비트 키. RC4 및 AES 알고리즘 모두 이 키 크기를 사용할 수 있습니다. |
| x256 | `2` | 256비트 키. 이러한 키 크기는 AES와 함께만 사용할 수 있으며 최신 Adobe Reader 버전(버전 9부터)에서 인식됩니다. |

### 또 보기

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


