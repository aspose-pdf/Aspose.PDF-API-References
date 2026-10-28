---
title: "Field.ExportValueToJson"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Field 메서드. 지정된 필드의 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지 않습니다."
type: docs
weight: 180
url: /ko/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

지정된 필드의 내용을 JSON 스트림으로 내보냅니다. 버튼 필드 값은 내보내지 않습니다.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputJsonStream | Stream | 필드 데이터가 기록될 출력 JSON 스트림. |
| indented | Boolean | 옵션. JSON 출력이 가독성을 위해 들여쓰기될지 여부를 지정합니다. 기본값은 true입니다. |

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### 또 보기

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


