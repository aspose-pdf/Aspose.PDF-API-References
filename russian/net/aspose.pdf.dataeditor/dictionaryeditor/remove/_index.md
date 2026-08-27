---
title: "DictionaryEditor.Remove"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод DictionaryEditor. Удаляет элемент с указанным ключом из DictionaryEditor"
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
| ключ | String | Ключ элемента, который нужно удалить. |

### Возвращаемое значение

True, если элемент успешно удалён; в противном случае — false. Этот метод также возвращает false, если ключ не найден в оригинальном словаре или ключ не редактируемый

### См. также

* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)

---

## Remove(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) {#remove}

Удаляет первое вхождение конкретного объекта из [`DictionaryEditor`](../).

```csharp
public bool Remove(KeyValuePair<string, ICosPdfPrimitive> item)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | KeyValuePair`2 | Объект для удаления из [`DictionaryEditor`](../). |

### Возвращаемое значение

true, если элемент был успешно удалён из [`DictionaryEditor`](../); в противном случае — false. Этот метод также возвращает false, если элемент не найден в оригинальном [`DictionaryEditor`](../).

### См. также

* interface [ICosPdfPrimitive](../../icospdfprimitive/)
* class [DictionaryEditor](../)
* namespace [Aspose.Pdf.DataEditor](../../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../../)


