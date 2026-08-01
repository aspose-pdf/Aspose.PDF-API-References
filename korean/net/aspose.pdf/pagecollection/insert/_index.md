---
title: "PageCollection.Insert"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PageCollection 메서드. 지정된 위치에 빈 페이지를 컬렉션에 삽입합니다. 문서에 크기가 다른 페이지가 이미 포함되어 있는 경우 가장 많이 나타나는 페이지의 크기가 선택됩니다. 두 종류의 페이지만 있는 경우 첫 번째 페이지의 크기가 사용됩니다."
type: docs
weight: 160
url: /ko/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

지정된 위치에 빈 페이지를 컬렉션에 삽입합니다. 문서에 크기가 다른 페이지가 이미 포함되어 있는 경우, 가장 많이 나타나는 페이지의 크기가 선택됩니다. 두 개의 서로 다른 페이지만 있는 경우, 첫 번째 페이지의 크기가 사용됩니다.

```csharp
public Page Insert(int pageNumber)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 새 페이지의 위치. |

### 반환 값

삽입된 페이지.

### 또 보기

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

지정된 위치에 페이지를 페이지 컬렉션에 삽입합니다.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 컬렉션에서 필요한 페이지 인덱스. |
| 엔터티 | 페이지 | 삽입될 페이지. |

### 반환 값

삽입된 페이지.

### 또 보기

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

컬렉션의 페이지를 문서에 삽입합니다.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 새 페이지의 시작 위치. |
| 페이지 | ICollection`1 | 페이지 컬렉션. |

### 또 보기

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

배열의 페이지를 문서에 삽입합니다.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | Int32 | 새 페이지의 시작 번호. |
| 페이지 | Page[] | 삽입될 페이지 배열. |

### 또 보기

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


