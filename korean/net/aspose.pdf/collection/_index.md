---
title: "클래스 Collection"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Collection 클래스. Collection12.3.5 컬렉션을 나타내는 클래스입니다."
type: docs
weight: 3130
url: /ko/net/aspose.pdf/collection/
---
## Collection class

Collection(12.3.5 Collections)에 대한 클래스를 나타냅니다.

```csharp
public class Collection : EmbeddedFileCollection
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Collection](collection/)() | 새 Collection 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | 컬렉션에 포함된 파일 수를 가져옵니다. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | 기본 포함 파일 이름입니다. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | 이 컬렉션에 대한 접근이 동기화(스레드 안전)되는지 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | 인덱스로 포함 파일을 가져옵니다. (2개의 인덱서) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | 파일 첨부 키 목록을 반환합니다. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | 문서 컬렉션의 "Schema"를 가져옵니다. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | 이 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | 컬렉션에 포함 파일 사양을 추가합니다. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | 지정된 키로 포함 파일에 파일을 추가합니다. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | FileSpecification 객체 배열을 컬렉션에 복사합니다. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | 문서에서 모든 포함된 파일을 제거합니다. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | 이름으로 포함된 파일을 삭제합니다. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | 컬렉션에서 해당 키를 사용하여 파일을 삭제합니다. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | 이름으로 포함된 파일을 반환합니다. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | 컬렉션 열거자를 반환합니다. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | 지정에 따라 정렬된 파일 컬렉션을 가져옵니다. |

### 또 보기

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


