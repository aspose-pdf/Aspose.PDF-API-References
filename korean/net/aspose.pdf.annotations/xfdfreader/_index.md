---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XfdfReader 클래스. XFDF 형식 읽기를 수행하는 클래스
type: docs
weight: 2740
url: /ko/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader 클래스

XFDF 형식 읽기를 수행하는 클래스입니다.

```csharp
public sealed class XfdfReader
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XfdfReader](xfdfreader/)() | 기본 생성자입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | XFDF 파일을 구문 분석하고 정보를 해시 테이블로 반환합니다. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | XFDF 파일에서 주석을 가져와 문서에 추가합니다. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | XFDF 파일에서 필드 값을 가져옵니다. |

## 예제

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### 참조

* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)