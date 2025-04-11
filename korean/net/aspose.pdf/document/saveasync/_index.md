---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: 문서 방법. 문서를 스트림에 저장합니다.
type: docs
weight: 840
url: /ko/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

문서를 스트림에 저장합니다.

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| output | Stream | 문서가 저장될 스트림입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

지정된 파일에 문서를 저장합니다.

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일의 경로입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

문서를 점진적으로 저장합니다(즉, 점진적 업데이트 기술을 사용하여).

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

## Remarks

문서를 점진적으로 저장하려면 문서 파일을 쓰기 위해 열어야 합니다. 따라서 Document는 다음 코드 조각과 같이 쓰기 가능한 스트림으로 초기화되어야 합니다: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // 일부 변경을 하고 문서를 점진적으로 저장합니다 doc.Save();

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

저장 옵션과 함께 문서를 저장합니다.

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | SaveOptions | 저장 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

### See Also

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

새 이름과 파일 형식으로 문서를 저장합니다.

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일의 경로입니다. |
| format | SaveFormat | 형식 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

### See Also

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

새 이름과 파일 형식으로 문서를 저장합니다.

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | 문서가 저장될 스트림입니다. |
| format | SaveFormat | 형식 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/)가 메서드에 전달될 때 ArgumentException이 발생합니다. HTML 스트림에 문서를 저장하는 것은 지원되지 않습니다. 파일에 저장하는 메서드를 사용하십시오. |

### See Also

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

새 이름으로 문서를 저장하고 저장 옵션을 설정합니다.

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFileName | String | 문서가 저장될 파일의 경로입니다. |
| options | SaveOptions | 저장 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

### See Also

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

저장 옵션과 함께 스트림에 문서를 저장합니다.

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | 문서가 저장될 스트림입니다. |
| options | SaveOptions | 저장 옵션입니다. |
| cancellationToken | CancellationToken | 취소 토큰입니다. |

### Return Value

비동기 작업입니다.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/)가 메서드에 전달될 때 ArgumentException이 발생합니다. HTML 스트림에 문서를 저장하는 것은 지원되지 않습니다. 파일에 저장하는 메서드를 사용하십시오. |

### See Also

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)