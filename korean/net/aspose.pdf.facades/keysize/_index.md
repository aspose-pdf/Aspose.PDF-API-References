---
title: Enum KeySize
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.KeySize 열. PDF 문서를 암호화하는 데 사용할 수 있는 다양한 키 크기를 정의합니다.
type: docs
weight: 4390
url: /ko/net/aspose.pdf.facades/keysize/
---
## KeySize 열거형

PDF 문서를 암호화하는 데 사용할 수 있는 다양한 키 크기를 정의합니다.

```csharp
public enum KeySize
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| x40 | `0` | 40 비트 키. 이러한 키 크기는 RC4 알고리즘과 함께 사용되며 낮은 수준의 보안을 제공합니다. 그럼에도 불구하고 오래된 버전의 PDF 문서는 이러한 키(버전 1.3 이하)로만 암호화할 수 있습니다. |
| x128 | `1` | 128 비트 키. RC4 및 AES 알고리즘 모두 이러한 키 크기를 사용할 수 있습니다. |
| x256 | `2` | 256 비트 키. 이러한 키 크기는 AES와 함께만 사용할 수 있으며 최신 Adobe Reader 버전(버전 9 이상)에서 인식됩니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)