---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 메서드. FDF 파일을 XML로 변환
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml 메서드

FDF 파일을 XML로 변환합니다.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFdf | Stream | 변환할 FDF가 포함된 스트림입니다. |
| destXml | Stream | 결과 XML이 배치될 소스입니다. |

## 예제

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### 참조

* 클래스 [FormDataConverter](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)