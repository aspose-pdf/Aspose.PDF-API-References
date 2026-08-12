---
title: "Aspose::Pdf::Forms::SignatureField::ExtractImage метод"
linktitle: "ExtractImage"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Forms::SignatureField::ExtractImage method. Извлекает изображение signature''s как поток JPEG‑закодированных данных в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.forms/signaturefield/extractimage/
---
## SignatureField::ExtractImage() method


Извлекает изображение подписи как поток, закодированный в JPEG.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage()
```


### ReturnValue

Если изображение было успешно найдено, возвращает объект потока JPEG‑закодированных данных; в противном случае — null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## SignatureField::ExtractImage(const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\&) method


Извлекает изображение подписи как закодированный поток.

```cpp
System::SharedPtr<System::IO::Stream> Aspose::Pdf::Forms::SignatureField::ExtractImage(const System::SharedPtr<System::Drawing::Imaging::ImageFormat> &format)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| format | const System::SharedPtr\<System::Drawing::Imaging::ImageFormat\>\& | формат [Image](../../../aspose.pdf/image/) для кодирования. |

### ReturnValue

Если изображение было успешно найдено, возвращает объект encodedstream; в противном случае — null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [ImageFormat](../../../system.drawing.imaging/imageformat/)
* Class [SignatureField](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
