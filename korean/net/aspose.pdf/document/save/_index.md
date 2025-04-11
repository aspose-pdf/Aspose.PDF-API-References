---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: 문서 메서드. 문서를 스트림에 저장합니다.
type: docs
weight: 830
url: /ko/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

문서를 스트림에 저장합니다.

```csharp
public void Save(Stream output)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| output | Stream | 문서가 저장될 스트림입니다. |

### 참조

* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

지정된 파일에 문서를 저장합니다.

```csharp
public void Save(string outputFileName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일의 경로입니다. |

### 참조

* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Save() {#save}

문서를 점진적으로 저장합니다(즉, 점진적 업데이트 기술을 사용하여).

```csharp
public void Save()
```

## 비고

문서를 점진적으로 저장하려면 문서 파일을 쓰기 위해 열어야 합니다. 따라서 Document는 다음 코드 조각과 같이 쓰기 가능한 스트림으로 초기화되어야 합니다: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // 일부 변경을 하고 문서를 점진적으로 저장합니다 doc.Save();

### 참조

* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

저장 옵션과 함께 문서를 저장합니다.

```csharp
public void Save(SaveOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| options | SaveOptions | 저장 옵션입니다. |

### 참조

* 클래스 [SaveOptions](../../saveoptions/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

새 이름과 파일 형식으로 문서를 저장합니다.

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일의 경로입니다. |
| format | SaveFormat | 형식 옵션입니다. |

### 참조

* 열거형 [SaveFormat](../../saveformat/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

새 이름과 파일 형식으로 문서를 저장합니다.

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 문서가 저장될 스트림입니다. |
| format | SaveFormat | 형식 옵션입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/)가 메서드에 전달될 때 ArgumentException이 발생합니다. HTML 스트림에 문서를 저장하는 것은 지원되지 않습니다. 파일에 저장하는 메서드를 사용하십시오. |

### 참조

* 열거형 [SaveFormat](../../saveformat/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

새 이름으로 문서를 저장하고 저장 옵션을 설정합니다.

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일의 경로입니다. |
| options | SaveOptions | 저장 옵션입니다. |

### 참조

* 클래스 [SaveOptions](../../saveoptions/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

저장 옵션과 함께 스트림에 문서를 저장합니다.

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 문서가 저장될 스트림입니다. |
| options | SaveOptions | 저장 옵션입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/)가 메서드에 전달될 때 ArgumentException이 발생합니다. HTML 스트림에 문서를 저장하는 것은 지원되지 않습니다. 파일에 저장하는 메서드를 사용하십시오. |

### 참조

* 클래스 [SaveOptions](../../saveoptions/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)