---
title: Enum ImageDeleteAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImageDeleteAction 열거형. 이미지가 컬렉션에서 제거될 때 이미지 객체에 대해 수행되는 작업. 이미지 객체가 제거되면
type: docs
weight: 5870
url: /ko/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction 열거형

이미지가 컬렉션에서 제거될 때 이미지 객체에 대해 수행되는 작업. 이미지 객체가 제거되면

```csharp
public enum ImageDeleteAction
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| KeepContents | `0` | 이미지가 컬렉션에서 제거됩니다. 페이지 내용에 이미지에 대한 참조가 포함되어 있으면 제거되지 않습니다. 문서가 유효하지 않을 수 있습니다. |
| None | `1` | 이미지가 컬렉션과 페이지 내용에서 제거되지만 이미지 객체는 삭제되지 않습니다. 파일 크기는 줄어들지 않습니다. |
| ForceDelete | `2` | 이미지가 컬렉션에서 제거되고 이미지 객체가 문서에서 제거됩니다. 동일한 객체에 대한 다른 참조가 존재하면 문서가 손상될 수 있습니다. |
| Check | `3` | 이미지가 컬렉션에서 제거되고 이미지 객체는 다른 페이지에서 이미지에 대한 다른 참조가 없을 경우에만 제거됩니다. 이는 ForceDelete 옵션에 비해 더 많은 시간이 소요될 수 있습니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)