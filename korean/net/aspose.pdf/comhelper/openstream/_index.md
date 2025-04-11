---
title: ComHelper.OpenStream
second_title: Aspose.PDF for .NET API Reference
description: ComHelper 메서드. 입력 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

입력 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다.

```csharp
public Document OpenStream(Stream input)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | Stream | PDF 문서가 포함된 스트림입니다. |

### 반환 값

Document 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

입력 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다.

```csharp
public Document OpenStream(Stream input, string password)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | Stream | 입력 스트림 객체, 해당 PDF는 비밀번호로 보호됩니다. |
| password | String | 사용자 또는 소유자 비밀번호입니다. |

### 반환 값

Document 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

입력 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다.

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | Stream | PDF 문서가 포함된 스트림입니다. |
| isManagedStream | Boolean | `true`로 설정하면 내부 스트림이 종료 전에 닫힙니다; 그렇지 않으면 닫히지 않습니다. |

### 반환 값

Document 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

입력 스트림에서 새 Document 인스턴스를 초기화하고 반환합니다.

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | Stream | PDF 문서가 포함된 스트림입니다. |
| password | String | 사용자 또는 소유자 비밀번호입니다. |
| isManagedStream | Boolean | `true`로 설정하면 내부 스트림이 종료 전에 닫힙니다; 그렇지 않으면 닫히지 않습니다. |

### 반환 값

Document 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

필요한 변환을 제공하여 스트림에서 기존 문서를 열고 반환합니다.

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| input | Stream | PDF 문서로 변환할 입력 스트림입니다. |
| options | LoadOptions | 입력을 PDF 문서로 변환하기 위한 속성을 나타냅니다. |

### 반환 값

Document 객체

### 참조

* 클래스 [Document](../../document/)
* 클래스 [LoadOptions](../../loadoptions/)
* 클래스 [ComHelper](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)