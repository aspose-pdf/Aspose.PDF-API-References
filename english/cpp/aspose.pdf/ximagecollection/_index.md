---
title: Aspose::Pdf::XImageCollection class
linktitle: XImageCollection
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XImageCollection class. Class representing XImage collection in C++.'
type: docs
weight: 19600
url: /cpp/aspose.pdf/ximagecollection/
---
## XImageCollection class


Class representing [XImage](../ximage/) collection.

```cpp
class XImageCollection : public System::Collections::Generic::ICollection<System::SharedPtr<Aspose::Pdf::XImage>>
```

## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(System::SharedPtr\<System::IO::Stream\>) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(System::SharedPtr\<Aspose::Pdf::BitmapInfo\>) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(System::SharedPtr\<System::IO::Stream\>, Aspose::Pdf::ImageFilterType) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(System::SharedPtr\<Aspose::Pdf::BitmapInfo\>, Aspose::Pdf::ImageFilterType) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [Add](./add/)(System::SharedPtr\<System::IO::Stream\>, int32_t) | Adds entity to the end of the collection, so entity can be accessed by the last index. |
| [AddWithName](./addwithname/)(System::SharedPtr\<Aspose::Pdf::XImage\>) | Adds new image to [Image](../image/) list. This method adds image as reference to the same PdfObject (which allows to decrease file size) |
| [Clear](./clear/)() override | Clears all items from the collection. |
| [Contains](./contains/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) const override | Determines whether the collection contains a specific value. |
| [CopyTo](./copyto/)(System::ArrayPtr\<System::SharedPtr\<Aspose::Pdf::XImage\>\>, int32_t) override | Copies array of images into collection. |
| [Delete](./delete/)(int32_t) | Removes index from collection by index. |
| [Delete](./delete/)(int32_t, Aspose::Pdf::ImageDeleteAction) | Removes image from collection by index performing action specified by action parameter. |
| [Delete](./delete/)(System::String) | Removes item from collection by name. |
| [Delete](./delete/)(System::String, Aspose::Pdf::ImageDeleteAction) | Removes item from collection by name. |
| [Delete](./delete/)() | Deletes images from collection. |
| [get_Count](./get_count/)() const override | Count of images in collection. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Gets a value indicating whether the collection is read-only. |
| [get_IsSynchronized](./get_issynchronized/)() | Returns true if object is synchronized. |
| [get_Names](./get_names/)() | Gets array of image names. |
| [get_SyncRoot](./get_syncroot/)() const | Returns synchronization object. |
| [GetEnumerator](./getenumerator/)() override | Returns collection enumerator. |
| [GetImageName](./getimagename/)(System::SharedPtr\<Aspose::Pdf::XImage\>) | Returns name in images list which is key of the given image. |
| [idx_get](./idx_get/)(int32_t) | Gets image from collection by its index. |
| [idx_get](./idx_get/)(System::String) | Gets image from collection by its name. |
| [Remove](./remove/)(const System::SharedPtr\<Aspose::Pdf::XImage\>\&) override | Removes item from collection, throws NotImplementedException
. |
| [Replace](./replace/)(int32_t, System::SharedPtr\<System::IO::Stream\>) | Replace image in collection with another image. |
| [Replace](./replace/)(int32_t, System::SharedPtr\<System::IO::Stream\>, int32_t, bool) | Replace image in collection with another image. |
| [Replace](./replace/)(int32_t, System::SharedPtr\<System::IO::Stream\>, int32_t) | Replace image in collection with another image. |
## See Also

* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
