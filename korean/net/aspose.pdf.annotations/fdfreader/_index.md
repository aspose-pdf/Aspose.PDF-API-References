---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FdfReader 클래스. FDF 형식 읽기를 수행하는 클래스
type: docs
weight: 1700
url: /ko/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader 클래스

FDF 형식 읽기를 수행하는 클래스입니다.

```csharp
public sealed class FdfReader
```

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | FDF 파일에서 주석을 가져와 문서에 넣습니다. |

## 예제

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### 참조

* 네임스페이스 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* 어셈블리 [Aspose.PDF](../../)