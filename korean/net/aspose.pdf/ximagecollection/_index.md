---
title: Class XImageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImageCollection 클래스. XImage 컬렉션을 나타내는 클래스
type: docs
weight: 11360
url: /ko/net/aspose.pdf/ximagecollection/
---
## XImageCollection 클래스

XImage 컬렉션을 나타내는 클래스입니다.

```csharp
public sealed class XImageCollection : ICollection<XImage>
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf/ximagecollection/count/) { get; } | 컬렉션의 이미지 수. |
| [IsReadOnly](../../aspose.pdf/ximagecollection/isreadonly/) { get; } | 컬렉션이 읽기 전용인지 여부를 나타내는 값을 가져옵니다. |
| [IsSynchronized](../../aspose.pdf/ximagecollection/issynchronized/) { get; } | 객체가 동기화되어 있으면 true를 반환합니다. |
| [Item](../../aspose.pdf/ximagecollection/item/) { get; } | 인덱스를 통해 컬렉션에서 이미지를 가져옵니다. (2개의 인덱서) |
| [Names](../../aspose.pdf/ximagecollection/names/) { get; } | 이미지 이름의 배열을 가져옵니다. |
| [SyncRoot](../../aspose.pdf/ximagecollection/syncroot/) { get; } | 동기화 객체를 반환합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf/ximagecollection/add/#add)(BitmapInfo) | 엔티티를 컬렉션의 끝에 추가하여 마지막 인덱스로 접근할 수 있게 합니다. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_3)(Stream) | 엔티티를 컬렉션의 끝에 추가하여 마지막 인덱스로 접근할 수 있게 합니다. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_2)(XImage) | 이미지 목록에 새 이미지를 추가합니다. 이 메서드는 이미지를 동일한 PdfObject에 대한 참조로 추가합니다(파일 크기를 줄일 수 있음). |
| [Add](../../aspose.pdf/ximagecollection/add/#add_1)(BitmapInfo, ImageFilterType) | 엔티티를 컬렉션의 끝에 추가하여 마지막 인덱스로 접근할 수 있게 합니다. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_4)(Stream, ImageFilterType) | 엔티티를 컬렉션의 끝에 추가하여 마지막 인덱스로 접근할 수 있게 합니다. |
| [Add](../../aspose.pdf/ximagecollection/add/#add_5)(Stream, int) | 엔티티를 컬렉션의 끝에 추가하여 마지막 인덱스로 접근할 수 있게 합니다. |
| [Clear](../../aspose.pdf/ximagecollection/clear/)() | 컬렉션에서 모든 항목을 지웁니다. |
| [Contains](../../aspose.pdf/ximagecollection/contains/)(XImage) | 컬렉션에 특정 값이 포함되어 있는지 확인합니다. |
| [CopyTo](../../aspose.pdf/ximagecollection/copyto/)(XImage[], int) | 이미지 배열을 컬렉션에 복사합니다. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete)() | 컬렉션에서 이미지를 삭제합니다. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_1)(int) | 인덱스를 통해 컬렉션에서 인덱스를 제거합니다. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_3)(string) | 이름을 통해 컬렉션에서 항목을 제거합니다. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_2)(int, ImageDeleteAction) | 지정된 작업 매개변수에 따라 인덱스를 통해 컬렉션에서 이미지를 제거합니다. |
| [Delete](../../aspose.pdf/ximagecollection/delete/#delete_4)(string, ImageDeleteAction) | 이름을 통해 컬렉션에서 항목을 제거합니다. |
| [GetEnumerator](../../aspose.pdf/ximagecollection/getenumerator/)() | 컬렉션 열거자를 반환합니다. |
| [GetImageName](../../aspose.pdf/ximagecollection/getimagename/)(XImage) | 주어진 이미지의 키인 이미지 목록에서 이름을 반환합니다. |
| [Remove](../../aspose.pdf/ximagecollection/remove/)(XImage) | 컬렉션에서 항목을 제거하며, NotImplementedException을 발생시킵니다. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace)(int, Stream) | 컬렉션의 이미지를 다른 이미지로 교체합니다. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_1)(int, Stream, int) | 컬렉션의 이미지를 다른 이미지로 교체합니다. |
| [Replace](../../aspose.pdf/ximagecollection/replace/#replace_2)(int, Stream, int, bool) | 컬렉션의 이미지를 다른 이미지로 교체합니다. |

### 참조

* 클래스 [XImage](../ximage/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)