---
title: Class FileSpecification
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FileSpecification 클래스. 임베디드 파일을 나타내는 클래스
type: docs
weight: 4850
url: /ko/net/aspose.pdf/filespecification/
---
## FileSpecification class

임베디드 파일을 나타내는 클래스.

```csharp
public sealed class FileSpecification : IDisposable
```

## Constructors

| Name | Description |
| --- | --- |
| [FileSpecification](filespecification/#constructor)() | 새로운 빈 파일 사양을 생성합니다. |
| [FileSpecification](filespecification/#constructor_3)(string) | FileSpecification의 생성자 |
| [FileSpecification](filespecification/#constructor_1)(Stream, string) | 파일 사양의 생성자. |
| [FileSpecification](filespecification/#constructor_4)(string, Annotation) | FileSpecification의 생성자. |
| [FileSpecification](filespecification/#constructor_5)(string, string) | FileSpecification의 생성자. |
| [FileSpecification](filespecification/#constructor_2)(Stream, string, string) | FileSpecification의 생성자. |

## Properties

| Name | Description |
| --- | --- |
| [AFRelationship](../../aspose.pdf/filespecification/afrelationship/) { get; set; } | 관련 파일 관계. |
| [CollectionItem](../../aspose.pdf/filespecification/collectionitem/) { get; } | 파일 사양의 컬렉션 항목을 가져옵니다. |
| [Contents](../../aspose.pdf/filespecification/contents/) { get; set; } | 내용 파일을 가져오거나 설정합니다. 이 속성은 메모리에 로드된 데이터를 반환하며, 대용량 데이터의 경우 메모리 부족 예외를 유발할 수 있습니다. 메모리 사용량을 줄이려면 StreamContents를 사용하십시오. |
| [Description](../../aspose.pdf/filespecification/description/) { get; set; } | 파일 사양과 관련된 텍스트를 가져오거나 설정합니다. |
| [Encoding](../../aspose.pdf/filespecification/encoding/) { get; set; } | 인코딩 형식을 가져오거나 설정합니다. 가능한 값: Zip - 파일이 ZIP으로 압축됨, None - 파일이 압축되지 않음. |
| [EncryptedPayload](../../aspose.pdf/filespecification/encryptedpayload/) { get; } | 암호화된 페이로드를 가져옵니다. |
| [FileSystem](../../aspose.pdf/filespecification/filesystem/) { get; set; } | 파일 시스템의 이름을 가져오거나 설정합니다. |
| [IncludeContents](../../aspose.pdf/filespecification/includecontents/) { get; set; } | true인 경우 파일의 내용이 파일 사양에 포함됩니다. |
| [MIMEType](../../aspose.pdf/filespecification/mimetype/) { get; set; } | 임베디드 파일의 하위 유형을 가져옵니다. |
| [Name](../../aspose.pdf/filespecification/name/) { get; set; } | 파일 사양 이름을 가져오거나 설정합니다. |
| [Params](../../aspose.pdf/filespecification/params/) { get; set; } | 파일 매개변수를 가져옵니다. |
| [StreamContents](../../aspose.pdf/filespecification/streamcontents/) { get; } | 파일의 내용을 스트림으로 가져옵니다. 내용은 메모리에 로드되지 않아 메모리 사용량을 줄일 수 있습니다. 그러나 이 스트림은 위치 지정 및 Length 속성을 지원하지 않습니다. 이러한 기능이 필요하면 대신 Contents 속성을 사용하십시오. |
| [UnicodeName](../../aspose.pdf/filespecification/unicodename/) { get; set; } | 파일 사양 유니코드 이름을 가져오거나 설정합니다. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.pdf/filespecification/dispose/)() | 내용을 폐기합니다. |
| [GetValue](../../aspose.pdf/filespecification/getvalue/)(string) | 애플리케이션 특정 매개변수를 가져옵니다. |
| [SetValue](../../aspose.pdf/filespecification/setvalue/)(string, string) | 애플리케이션 특정 매개변수를 설정합니다. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)