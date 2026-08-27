---
title: "클래스 FdfReader"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Annotations.FdfReader 클래스. FDF 형식 읽기를 수행하는 클래스"
type: docs
weight: 1790
url: /ko/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

FDF 형식 읽기를 수행하는 클래스.

```csharp
public sealed class FdfReader
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | FDF 파일에서 주석을 가져와 문서에 삽입합니다. |

## 예제

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### 또 보기

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


