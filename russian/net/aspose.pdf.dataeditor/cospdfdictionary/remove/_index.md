---
title: CosPdfDictionary.Remove
second_title: Aspose.PDF for .NET API Reference
description: Метод CosPdfDictionary. Удаляет элемент с указанным ключом из CosPdfDictionary
type: docs
weight: 150
url: /ru/net/aspose.pdf.dataeditor/cospdfdictionary/remove/
---
## Remove(string) {#remove_1}

Удаляет элемент с указанным ключом из [`CosPdfDictionary`](../).

```csharp
public bool Remove(string key)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | String | Ключ элемента, который нужно удалить. |

### Возвращаемое значение

True, если элемент успешно удален; в противном случае false. Этот метод также возвращает false, если ключ не найден в оригинальном словаре или ключ не подлежит редактированию.

### См. также

* класс [CosPdfDictionary](../)
* пространство имен [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Удаляет первое вхождение конкретного объекта из [`CosPdfDictionary`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Объект, который нужно удалить из [`CosPdfDictionary`](../). |

### Возвращаемое значение

true, если item был успешно удален из [`CosPdfDictionary`](../); в противном случае false. Этот метод также возвращает false, если item не найден в оригинальном [`CosPdfDictionary`](../).

### См. также

* интерфейс [ICosPdfPrimitive](../../icospdfprimitive/)
* класс [CosPdfDictionary](../)
* пространство имен [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../../)