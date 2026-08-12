---
title: "Aspose::Pdf::XImageCollection class"
linktitle: "XImageCollection"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::XImageCollection class. Класс, представляющий коллекцию XImage в C++."
type: docs
weight: 19900
url: /ru/cpp/aspose.pdf/ximagecollection/
---
## XImageCollection class


Класс, представляющий коллекцию [XImage](../ximage/).

```cpp
class XImageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Aspose::Pdf::XImage>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&) | Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу. |
| [Add](./add/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&) | Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу. |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&, Aspose::Pdf::ImageFilterType) | Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу. |
| [Add](./add/)(const System::SharedPtr\<Aspose::Pdf::BitmapInfo\>\&, Aspose::Pdf::ImageFilterType) | Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу. |
| [Add](./add/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Добавляет элемент в конец коллекции, чтобы к элементу можно было обратиться по последнему индексу. |
| [AddWithName](./addwithname/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Добавляет новое изображение в список [Image](../image/). Этот метод добавляет изображение как ссылку на тот же PdfObject (что позволяет уменьшить размер файла) |
| [Clear](./clear/)() override | Очищает все элементы из коллекции. |
| [Contains](./contains/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) const override | Определяет, содержит ли коллекция определённое значение. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Aspose::Pdf::XImage\>\>, int32_t) override | Копирует массив изображений в коллекцию. |
| [Delete](./delete/)(int32_t) | Удаляет элемент из коллекции по индексу. |
| [Delete](./delete/)(int32_t, Aspose::Pdf::ImageDeleteAction) | Удаляет изображение из коллекции по индексу, выполняя действие, указанное параметром action. |
| [Delete](./delete/)(const System::String\&) | Удаляет элемент из коллекции по имени. |
| [Delete](./delete/)(const System::String\&, Aspose::Pdf::ImageDeleteAction) | Удаляет элемент из коллекции по имени. |
| [Delete](./delete/)() | Удаляет изображения из коллекции. |
| [get_Count](./get_count/)() const override | Количество изображений в коллекции. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Получает значение, указывающее, является ли коллекция только для чтения. |
| [get_IsSynchronized](./get_issynchronized/)() | Возвращает true, если объект синхронизирован. |
| [get_Names](./get_names/)() | Получает массив имен изображений. |
| [get_SyncRoot](./get_syncroot/)() const | Возвращает объект синхронизации. |
| [GetEnumerator](./getenumerator/)() override | Возвращает перечислитель коллекции. |
| [GetImageName](./getimagename/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) | Возвращает имя в списке изображений, которое является ключом данного изображения. |
| [idx_get](./idx_get/)(int32_t) | Получает изображение из коллекции по его индексу. |
| [idx_get](./idx_get/)(const System::String\&) | Получает изображение из коллекции по его имени. |
|  | [Remove](./remove/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) override | Удаляет элемент из коллекции, бросает NotImplementedException |
. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&) | Заменить изображение в коллекции другим изображением. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, bool) | Заменить изображение в коллекции другим изображением. |
| [Replace](./replace/)(int32_t, const System::SharedPtr\<System::IO::Stream\>\&, int32_t) | Заменить изображение в коллекции другим изображением. |
## См. также

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
