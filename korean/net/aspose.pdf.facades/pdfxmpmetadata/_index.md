---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfXmpMetadata 클래스. XMP 메타데이터 조작을 위한 클래스
type: docs
weight: 4640
url: /ko/net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata 클래스

XMP 메타데이터 조작을 위한 클래스.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | PdfXmpMetadata의 생성자. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | *document*를 기반으로 새로운 `PdfXmpMetadata` 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | 컬렉션의 항목 수를 가져옵니다. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 작업 중인 문서 파사드를 가져옵니다. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | 확장 필드의 사전을 가져옵니다. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | 컬렉션이 고정 크기를 가지면 true를 반환합니다. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | 컬렉션이 읽기 전용이면 true를 반환합니다. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | 컬렉션이 동기화되어 있으면 true를 반환합니다. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | 키로 값을 가져오거나 설정합니다. (2개의 인덱서) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | 사전에서 키를 가져옵니다. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | 컬렉션의 동기화 객체를 가져옵니다. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | 사전의 값 컬렉션을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | 키와 값을 쌍으로 사전에 추가합니다. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | XMP 메타데이터에 값을 추가합니다. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | 사전 객체에 새 요소를 추가합니다. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | 사전 객체에 새 요소를 추가합니다. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | 메타데이터에 확장 필드를 추가합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | 파사드를 초기화합니다. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | 파사드를 초기화합니다. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | 객체에서 모든 요소를 제거합니다. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | 파사드와 연결된 Aspose.Pdf.Document를 폐기합니다. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | 사전에 지정된 속성이 포함되어 있는지 확인합니다. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | 지정된 키-값 쌍이 사전에 포함되어 있는지 확인합니다. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | 사전에 지정된 키가 포함되어 있는지 확인합니다. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | 이 사전에 지정된 키가 포함되어 있는지 확인합니다. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | 파사드를 폐기합니다. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | 사전의 열거자 객체를 가져옵니다. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | 접두사로 네임스페이스 URI를 가져옵니다. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | 네임스페이스 URI로 접두사를 가져옵니다. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | 입력 PDF의 XmpMetadata를 XML 형식으로 가져옵니다. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | 메타 이름에 따라 입력 PDF의 XmpMetadata의 일부를 가져옵니다. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | 네임스페이스 URI를 등록합니다. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | 지정된 키로 요소를 제거합니다. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | 컬렉션에서 키/값 쌍을 제거합니다. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | 사전에서 키를 제거합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | PDF 문서를 지정된 스트림에 저장합니다. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | PDF 문서를 지정된 파일에 저장합니다. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | 사전에서 키를 찾으려고 시도하고, 발견되면 값을 검색합니다. |

### 참조

* class [SaveableFacade](../saveablefacade/)
* class [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)