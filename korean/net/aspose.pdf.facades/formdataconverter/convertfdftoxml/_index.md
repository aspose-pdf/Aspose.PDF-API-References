---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FormDataConverter 메서드. FDF 파일을 XML로 변환합니다."
type: docs
weight: 120
url: /ko/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml method

FDF 파일을 XML로 변환합니다.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sourceFdf | Stream | 변환할 FDF를 포함하는 스트림. |
| destXml | Stream | 결과 XML이 배치될 위치. |

## 예제

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### 또 보기

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


