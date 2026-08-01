---
title: "Document.Save"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 메서드. 저장 옵션을 사용하여 문서를 스트림에 저장합니다."
type: docs
weight: 850
url: /ko/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

저장 옵션을 사용하여 문서를 스트림에 저장합니다.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 문서가 저장될 스트림. |
| 옵션 | SaveOptions | 저장 옵션. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 메서드에 [`HtmlSaveOptions`](../../htmlsaveoptions/)가 전달될 때 ArgumentException이 발생합니다. 문서를 HTML 스트림에 저장하는 것은 지원되지 않습니다. 파일에 저장하는 메서드를 사용하십시오. |

### 또 보기

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save_2}

문서를 스트림에 저장합니다.

```csharp
public void Save(Stream output)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | Stream | 문서가 저장될 스트림. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

문서를 지정된 파일에 저장합니다.

```csharp
public void Save(string outputFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일 경로. |

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

문서를 증분 방식으로 저장합니다(예: 증분 업데이트 기술 사용).

```csharp
public void Save()
```

## 비고

문서를 증분 저장하려면 문서 파일을 쓰기 모드로 열어야 합니다. 따라서 Document는 다음 코드 스니펫과 같이 쓰기 가능한 스트림으로 초기화되어야 합니다: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // 일부 변경을 수행하고 문서를 증분 저장합니다 doc.Save();

### 또 보기

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

저장 옵션을 사용하여 문서를 저장합니다.

```csharp
public void Save(SaveOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 옵션 | SaveOptions | 저장 옵션. |

### 또 보기

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

새 이름과 파일 형식을 지정하여 문서를 저장합니다.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일 경로. |
| 포맷 | SaveFormat | 포맷 옵션. |

### 또 보기

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

새 이름과 파일 형식을 지정하여 문서를 저장합니다.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 문서가 저장될 스트림. |
| 포맷 | SaveFormat | 포맷 옵션. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | 메서드에 [`HtmlSaveOptions`](../../htmlsaveoptions/)가 전달될 때 ArgumentException이 발생합니다. 문서를 HTML 스트림에 저장하는 것은 지원되지 않습니다. 파일에 저장하는 메서드를 사용하십시오. |

### 또 보기

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

새 이름을 지정하고 저장 옵션을 설정하여 문서를 저장합니다.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일 경로. |
| 옵션 | SaveOptions | 저장 옵션. |

### 또 보기

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


