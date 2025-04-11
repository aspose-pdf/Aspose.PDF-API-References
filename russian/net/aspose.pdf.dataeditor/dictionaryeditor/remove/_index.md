---
title: DictionaryEditor.Remove
second_title: Aspose.PDF for .NET API Reference
description: Метод DictionaryEditor. Удаляет элемент с указанным ключом из DictionaryEditor
type: docs
weight: 140
url: /ru/net/aspose.pdf.dataeditor/dictionaryeditor/remove/
---
## Remove(string) {#remove_1}

Удаляет элемент с указанным ключом из [`DictionaryEditor`](../).

```csharp
public bool Remove(string key)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| key | String | Ключ элемента, который нужно удалить. |

### Возвращаемое значение

True, если элемент успешно удален; в противном случае false. Этот метод также возвращает false, если ключ не найден в оригинальном словаре или ключ не подлежит редактированию.

### См. также

* класс [DictionaryEditor](../)
* пространство имен [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Удаляет первое вхождение конкретного объекта из [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Объект, который нужно удалить из [`DictionaryEditor`](../). |

### Возвращаемое значение

true, если item был успешно удален из [`DictionaryEditor`](../); в противном случае false. Этот метод также возвращает false, если item не найден в оригинальном [`DictionaryEditor`](../).

### См. также

* интерфейс [ICosPdfPrimitive](../../icospdfprimitive/)
* класс [DictionaryEditor](../)
* пространство имен [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* сборка [Aspose.PDF](../../../)