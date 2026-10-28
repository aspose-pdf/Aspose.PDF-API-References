---
title: "열거형 ImageDeleteAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.ImageDeleteAction 열거형. 이미지가 컬렉션에서 제거될 때 이미지 객체에 수행되는 작업입니다. 이미지 객체가 제거되면"
type: docs
weight: 6000
url: /ko/net/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enumeration

이미지 객체가 컬렉션에서 제거될 때 이미지 객체와 함께 수행되는 작업입니다. 이미지 객체가 제거되면

```csharp
public enum ImageDeleteAction
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| KeepContents | `0` | 이미지는 컬렉션에서 제거됩니다. 페이지 내용에 이미지에 대한 참조가 포함되어 있으면 해당 참조는 제거되지 않습니다. 문서가 무효가 될 수 있습니다. |
| None | `1` | 이미지는 컬렉션 및 페이지 내용에서 제거되지만 이미지 객체는 삭제되지 않습니다. 파일 크기가 감소하지 않습니다. |
| ForceDelete | `2` | 이미지는 컬렉션에서 제거되고 이미지 객체는 문서에서 제거됩니다. 동일한 객체에 다른 참조가 존재하면 문서가 손상될 수 있습니다. |
| Check | `3` | 이미지는 컬렉션에서 제거되며 이미지 객체는 다른 페이지에서 이미지에 대한 다른 참조가 없을 경우에만 제거됩니다. 이는 ForceDelete 옵션에 비해 더 많은 시간이 걸릴 수 있습니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


