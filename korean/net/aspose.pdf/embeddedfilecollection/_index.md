---
title: Class EmbeddedFileCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EmbeddedFileCollection 클래스. 임베디드 파일 컬렉션을 나타내는 클래스
type: docs
weight: 4010
url: /ko/net/aspose.pdf/embeddedfilecollection/
---
## EmbeddedFileCollection class

임베디드 파일 컬렉션을 나타내는 클래스.

```csharp
public class EmbeddedFileCollection : ICollection<FileSpecification>
```

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | 컬렉션에 있는 임베디드 파일의 수를 가져옵니다. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | 이 컬렉션에 대한 접근이 동기화되었는지(스레드 안전) 여부를 나타내는 값을 가져옵니다. |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | 인덱스를 통해 임베디드 파일을 가져옵니다. (2개의 인덱서) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | 파일 첨부 키 목록을 반환합니다. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | 이 컬렉션에 대한 접근을 동기화하는 데 사용할 수 있는 객체를 가져옵니다. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add)(FileSpecification) | 임베디드 파일 사양을 컬렉션에 추가합니다. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/#add_1)(string, FileSpecification) | 지정된 키로 임베디드 파일에 파일을 추가합니다. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | FileSpecification 객체 배열을 컬렉션에 복사합니다. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete)() | 문서에서 모든 임베디드 파일을 제거합니다. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/#delete_1)(string) | 이름으로 임베디드 파일을 삭제합니다. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | 컬렉션에서 키로 파일을 삭제합니다. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | 이름으로 임베디드 파일을 반환합니다. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | 컬렉션 열거자를 반환합니다. |

### See Also

* class [FileSpecification](../filespecification/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)