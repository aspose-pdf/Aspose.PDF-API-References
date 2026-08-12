---
title: "Aspose::Pdf::Annotations::AppearanceDictionary класс"
linktitle: "AppearanceDictionary"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Annotations::AppearanceDictionary класс. Словарь внешнего вида аннотации, определяющий, как аннотация будет визуально представлена на странице в C++."
type: docs
weight: 900
url: /ru/cpp/aspose.pdf.annotations/appearancedictionary/
---
## AppearanceDictionary class


[Annotation](../annotation/) appearance dictionary specifying how the annotation shall be presented visually on the page.

```cpp
class AppearanceDictionary : public System::Collections::Generic::IDictionary<System::String, System::SharedPtr<XForm>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::String\&, const System::SharedPtr\<XForm\>\&) override | Добавить X‑форму для указанного ключа. |
| [Add](./add/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Добавляет пару ключ‑значение в словарь. |
| [Clear](./clear/)() override | Удаляет все элементы из словаря. |
| [Contains](./contains/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) const override | Проверяет, содержится ли указанная пара ключ‑значение в словаре. |
| [ContainsKey](./containskey/)(const System::String\&) const override | Определяет, содержит ли этот словарь указанный ключ. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<System::SharedPtr\<XForm\>\>\&, int32_t) | Копирует элементы словаря в массив, начиная с указанного индекса массива. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\>, int32_t) override | Копирует элементы ICollection в массив, начиная с указанного индекса массива. |
| [get_Count](./get_count/)() const override | Получает количество элементов, содержащихся в словаре. |
| [get_IsFixedSize](./get_isfixedsize/)() const | Получает значение, указывающее, имеет ли словарь фиксированный размер. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли словарь только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Получает значение, указывающее, синхронизирован ли доступ к словарю (потокобезопасный). |
| [get_Keys](./get_keys/)() const override | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [Keys](../) contains (N | R | Значения D).state, где N — обычный внешний вид, R — внешний вид при наведении, D — внешний вид при нажатии, а state — имя состояния (например, On, Off для флажков). |
| [get_SyncRoot](./get_syncroot/)() const | Получает объект, который можно использовать для синхронизации доступа к словарю. |
| [get_Values](./get_values/)() const override | Получает список значений словаря. Коллекция результата содержит список объектов [XForm](../../aspose.pdf/xform/). |
| [GetEnumerator](./getenumerator/)() override | Возвращает объект IDictionaryEnumerator для словаря. |
| [idx_get](./idx_get/)(const System::String\&) const override | Представляет удобную форму для получения потоков внешнего вида. |
| [idx_set](./idx_set/)(const System::String\&, System::SharedPtr\<XForm\>) override | Представляет удобную форму для получения потоков внешнего вида. |
| [Remove](./remove/)(const System::String\&) override | Удаляет ключ из словаря. |
| [Remove](./remove/)(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<XForm\>\>\&) override | Удаляет пару ключ/значение из коллекции. |
| [TryGetValue](./trygetvalue/)(const System::String\&, System::SharedPtr\<XForm\>\&) const override | Пытается найти ключ в словаре и получить значение, если найден. |
## См. также

* Class [IDictionary](../../system.collections.generic/idictionary/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
