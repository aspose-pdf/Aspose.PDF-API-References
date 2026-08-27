---
title: "Form.Form"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Form 생성자. 매개변수 없이 Form을 생성합니다."
type: docs
weight: 10
url: /ko/net/aspose.pdf.facades/form/form/
---
## Form() {#constructor}

매개변수 없이 Form의 생성자입니다.

```csharp
Form form = new Aspose.Pdf.Facades.Form();
form.SrcFileName = "file.pdf";
```

```csharp
public Form()
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(string) {#constructor_7}

Form의 생성자입니다.

```csharp
public Form(string srcFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcFileName | String | 소스 파일 경로입니다. |

## 예제

```csharp
Form form = new Form("PdfForm.pdf");
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Stream) {#constructor_4}

양식에 대한 생성자입니다.

```csharp
public Form(Stream srcStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcStream | Stream | 소스 스트림입니다. |

## 예제

```csharp
Form form = new Form(new FileStream("PdfForm.pdf", FileMode.Open, FileAccess.Read));
```

### 또 보기

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Form(Document) {#constructor_1}

새 [`Form`](../) 객체를 *document* 기반으로 초기화합니다.

```csharp
public Form(Document document)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| document | Document | Pdf 문서. |

### 또 보기

* class [Document](../../../aspose.pdf/document/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


