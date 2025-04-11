---
title: XImageCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: XImageCollection 메서드. 이미지 목록에 새 이미지를 추가합니다. 이 메서드는 파일 크기를 줄일 수 있도록 동일한 PdfObject에 대한 참조로 이미지를 추가합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf/ximagecollection/add/
---
## Add(XImage) {#add_2}

이미지를 이미지 목록에 추가합니다. 이 메서드는 파일 크기를 줄일 수 있도록 동일한 PdfObject에 대한 참조로 이미지를 추가합니다.

```csharp
public string Add(XImage image)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | XImage | 추가할 XImage입니다. |

### 반환 값

추가된 이미지의 이름입니다.

### 참조

* 클래스 [XImage](../../ximage/)
* 클래스 [XImageCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Add(Stream) {#add_3}

컬렉션의 끝에 엔터티를 추가하므로 엔터티는 마지막 인덱스로 접근할 수 있습니다.

```csharp
public string Add(Stream image)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | Stream | 이미지 데이터가 포함된 스트림( JPEG 형식). |

### 반환 값

추가된 이미지의 이름입니다.

### 참조

* 클래스 [XImageCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Add(BitmapInfo) {#add}

컬렉션의 끝에 엔터티를 추가하므로 엔터티는 마지막 인덱스로 접근할 수 있습니다.

```csharp
public string Add(BitmapInfo bitmapInfo)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | 픽셀 배열과 비트맵 정보(너비, 높이, 픽셀 형식)를 포함하는 객체입니다. |

### 반환 값

추가된 이미지의 이름입니다.

### 참조

* 클래스 [BitmapInfo](../../bitmapinfo/)
* 클래스 [XImageCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Add(Stream, ImageFilterType) {#add_4}

컬렉션의 끝에 엔터티를 추가하므로 엔터티는 마지막 인덱스로 접근할 수 있습니다.

```csharp
public string Add(Stream image, ImageFilterType filterType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | Stream | 이미지 데이터가 포함된 스트림입니다. |
| filterType | ImageFilterType | 이미지 필터 유형입니다. |

### 반환 값

추가된 이미지의 이름입니다.

### 참조

* 열거형 [ImageFilterType](../../imagefiltertype/)
* 클래스 [XImageCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Add(BitmapInfo, ImageFilterType) {#add_1}

컬렉션의 끝에 엔터티를 추가하므로 엔터티는 마지막 인덱스로 접근할 수 있습니다.

```csharp
public string Add(BitmapInfo bitmapInfo, ImageFilterType filterType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bitmapInfo | BitmapInfo | 픽셀 배열과 비트맵 정보(너비, 높이, 픽셀 형식)를 포함하는 객체입니다. |
| filterType | ImageFilterType | 이미지 필터 유형입니다. |

### 반환 값

추가된 이미지의 이름입니다.

### 참조

* 클래스 [BitmapInfo](../../bitmapinfo/)
* 열거형 [ImageFilterType](../../imagefiltertype/)
* 클래스 [XImageCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Add(Stream, int) {#add_5}

컬렉션의 끝에 엔터티를 추가하므로 엔터티는 마지막 인덱스로 접근할 수 있습니다.

```csharp
public void Add(Stream image, int quality)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| image | Stream | 이미지 데이터가 포함된 스트림( JPEG 형식). |
| quality | Int32 | JPEG 품질입니다. |

### 참조

* 클래스 [XImageCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)