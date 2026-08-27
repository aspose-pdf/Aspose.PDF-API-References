---
title: "Field.ImportValueFromJson"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Field 메서드. 필드 전체 이름과 정확히 일치하는 JSON 스트림에서 지정된 필드로 데이터를 가져옵니다."
type: docs
weight: 210
url: /ko/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

필드 전체 이름이 정확히 일치하는 경우 JSON 스트림에서 지정된 필드로 데이터를 가져옵니다.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputJsonStream | Stream | 필드에 가져올 필드 데이터를 포함하는 입력 JSON 스트림. |

### 반환 값

JSON 스트림에서 필드를 찾으면 true; 그렇지 않으면 false

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### 또 보기

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

'fieldFullNameInJSON' 변수에 지정된 전체 이름을 사용하여 JSON 스트림에서 지정된 필드로 데이터를 가져옵니다.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| inputJsonStream | Stream | 필드에 가져올 필드 데이터를 포함하는 입력 JSON 스트림. |
| fieldFullNameInJSON | String | JSON 스트림 내에서 일치시키기 위한 데이터의 이름입니다. JSON 스트림 내 데이터가 중첩 구조를 가지고 있는 경우, 전체 이름은 모든 상위 및 하위 항목을 '.' 로 구분하여 지정해야 합니다. |

### 반환 값

json 파일에서 필드를 찾은 경우 True; 그렇지 않으면 - false

## 예제

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### 또 보기

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


