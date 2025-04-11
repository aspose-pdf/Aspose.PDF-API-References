---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection 메서드. 컬렉션에서 연산자를 삭제합니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

컬렉션에서 연산자를 삭제합니다.

```csharp
public void Delete(int index)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| index | Int32 | 삭제해야 하는 연산자의 인덱스. 연산자 번호는 1부터 시작합니다. |

## 예제

예제는 인덱스를 사용하여 연산자를 삭제하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### 참조

* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

컬렉션에서 연산자를 삭제합니다.

```csharp
public void Delete(Operator[] ops)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| ops | Operator[] | 삭제할 연산자 배열 |

## 예제

예제는 페이지 내용에서 연산자를 제거하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

컬렉션에서 연산자를 삭제합니다.

```csharp
public void Delete(IList<Operator> list)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| list | IList`1 | 삭제할 연산자 목록 |

## 예제

예제는 페이지 내용에서 연산자를 제거하는 방법을 보여줍니다.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### 참조

* 클래스 [Operator](../../operator/)
* 클래스 [OperatorCollection](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)