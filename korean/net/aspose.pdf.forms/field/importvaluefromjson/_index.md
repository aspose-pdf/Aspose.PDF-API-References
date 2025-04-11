---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: 필드 메서드. 필드의 전체 이름과 정확히 일치하는 JSON 스트림에서 지정된 필드로 데이터를 가져옵니다.
type: docs
weight: 210
url: /ko/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

JSON 스트림에서 지정된 필드로 데이터를 가져오며, 필드의 전체 이름과 정확히 일치하는 경우에만 수행됩니다.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputJsonStream | Stream | 필드로 가져올 필드 데이터가 포함된 입력 JSON 스트림입니다. |

### 반환 값

JSON 스트림에서 필드를 찾으면 true; 그렇지 않으면 false입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### 참조

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

JSON 스트림에서 지정된 필드로 데이터를 가져오며, 'fieldFullNameInJSON' 변수에 지정된 전체 이름을 사용하여 일치시킵니다.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputJsonStream | Stream | 필드로 가져올 필드 데이터가 포함된 입력 JSON 스트림입니다. |
| fieldFullNameInJSON | String | 일치를 위한 JSON 스트림 내 데이터의 이름입니다. JSON 스트림 내 데이터가 중첩 구조를 가지는 경우, 전체 이름은 모든 부모 및 자식 항목이 '.'로 구분되어 지정되어야 합니다. |

### 반환 값

JSON 파일에서 필드를 찾으면 true; 그렇지 않으면 false입니다.

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### 참조

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)