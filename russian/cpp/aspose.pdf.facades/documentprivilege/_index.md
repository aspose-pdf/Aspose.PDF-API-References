---
title: "Aspose::Pdf::Facades::DocumentPrivilege класс"
linktitle: "DocumentPrivilege"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::Facades::DocumentPrivilege класс. Представляет привилегии для доступа к файлу Pdf. См. toPdfFileSecurity. Существует 4 способа использования этого класса: 1. Использовать предопределённую привилегию напрямую. 2. На основе предопределённой привилегии и изменить некоторые конкретные разрешения. 3. На основе предопределённой привилегии и изменить комбинацию некоторых конкретных разрешений Adobe Professional. 4. Сочетает way2 и way3 в C++."
type: docs
weight: 500
url: /ru/cpp/aspose.pdf.facades/documentprivilege/
---
## DocumentPrivilege class


Представляет привилегии для доступа к файлу [Pdf](../../aspose.pdf/) . См. [PdfFileSecurity](../pdffilesecurity/). Существует 4 способа использования этого класса: 1. Использовать предопределённую привилегию напрямую. 2. На основе предопределённой привилегии и изменить некоторые конкретные разрешения. 3. На основе предопределённой привилегии и изменить комбинацию некоторых конкретных разрешений Adobe Professional. 4. Сочетает way2 и way3.

```cpp
class DocumentPrivilege : public System::IComparable<System::SharedPtr<System::Object>>
```

## Методы

| Метод | Описание |
| --- | --- |
| [CompareTo](./compareto/)(System::SharedPtr\<System::Object\>) override | Сравнивает два объекта [DocumentPrivilege](./). |
| static [get_AllowAll](./get_allowall/)() | Все разрешено. |
| [get_AllowAssembly](./get_allowassembly/)() | Устанавливает разрешение, позволяющее сборку или нет. true — разрешено, false — запрещено. |
| [get_AllowCopy](./get_allowcopy/)() | Устанавливает разрешение, позволяющее копировать или нет. true — разрешено, false — запрещено. |
| [get_AllowDegradedPrinting](./get_allowdegradedprinting/)() | Устанавливает разрешение, позволяющее печать в пониженном качестве или нет. true — разрешено, false — запрещено. |
| [get_AllowFillIn](./get_allowfillin/)() | Устанавливает разрешение, позволяющее заполнять формы или нет. true — разрешено, false — запрещено. |
| [get_AllowModifyAnnotations](./get_allowmodifyannotations/)() | Устанавливает разрешение, позволяющее изменять аннотации или нет. true означает разрешено, а false — запрещено. |
| [get_AllowModifyContents](./get_allowmodifycontents/)() | Устанавливает разрешение, позволяющее изменять содержимое или нет. true означает разрешено, а false — запрещено. |
| [get_AllowPrint](./get_allowprint/)() | Устанавливает разрешение на печать или его отсутствие. true означает разрешено, а false — запрещено. |
| [get_AllowScreenReaders](./get_allowscreenreaders/)() | Устанавливает разрешение для экранных читалок или нет. true означает разрешено, а false — запрещено. |
| static [get_Assembly](./get_assembly/)() | Разрешает сборку файла. |
| [get_ChangeAllowLevel](./get_changeallowlevel/)() | Получает и задает уровень изменения привилегий документа. Аналогично настройкам Changes Allowed в Adobe Professional. 0: Нет. 1: Вставка, удаление и вращение страниц. 2: Заполнение полей формы и подпись существующих полей подписи. 3: Комментирование, заполнение полей формы и подпись существующих полей подписи. 4: Всё, кроме извлечения страниц. |
| static [get_Copy](./get_copy/)() | Разрешает копирование файла. |
| [get_CopyAllowLevel](./get_copyallowlevel/)() | Получает и задает уровень копирования привилегий документа. Аналогично настройкам разрешений в Adobe Professional. 0: Нет. 1: Включить доступ к тексту для устройств экранных читалок для слабовидящих. 2: Включить копирование текста, изображений и другого контента. |
| static [get_DegradedPrinting](./get_degradedprinting/)() | Разрешает печать низкого качества. |
| static [get_FillIn](./get_fillin/)() | Разрешает заполнение форм в файле. |
| static [get_ForbidAll](./get_forbidall/)() | Все запрещено. |
| static [get_ModifyAnnotations](./get_modifyannotations/)() | Разрешает изменение аннотаций файла. |
| static [get_ModifyContents](./get_modifycontents/)() | Разрешает изменение файла. |
| static [get_Print](./get_print/)() | Разрешает печать файла. |
| [get_PrintAllowLevel](./get_printallowlevel/)() | Получает и задает уровень печати привилегий документа. Аналогично настройкам Printing Allowed в Adobe Professional. 0: Нет. 1: Низкое разрешение (150 dpi). 2: Высокое разрешение. |
| static [get_ScreenReaders](./get_screenreaders/)() | Разрешает только чтение на экране. |
| [set_AllowAssembly](./set_allowassembly/)(bool) | Устанавливает разрешение, позволяющее сборку или нет. true — разрешено, false — запрещено. |
| [set_AllowCopy](./set_allowcopy/)(bool) | Устанавливает разрешение, позволяющее копировать или нет. true — разрешено, false — запрещено. |
| [set_AllowDegradedPrinting](./set_allowdegradedprinting/)(bool) | Устанавливает разрешение, позволяющее печать в пониженном качестве или нет. true — разрешено, false — запрещено. |
| [set_AllowFillIn](./set_allowfillin/)(bool) | Устанавливает разрешение, позволяющее заполнять формы или нет. true — разрешено, false — запрещено. |
| [set_AllowModifyAnnotations](./set_allowmodifyannotations/)(bool) | Устанавливает разрешение, позволяющее изменять аннотации или нет. true означает разрешено, а false — запрещено. |
| [set_AllowModifyContents](./set_allowmodifycontents/)(bool) | Устанавливает разрешение, позволяющее изменять содержимое или нет. true означает разрешено, а false — запрещено. |
| [set_AllowPrint](./set_allowprint/)(bool) | Устанавливает разрешение на печать или его отсутствие. true означает разрешено, а false — запрещено. |
| [set_AllowScreenReaders](./set_allowscreenreaders/)(bool) | Устанавливает разрешение для экранных читалок или нет. true означает разрешено, а false — запрещено. |
| [set_ChangeAllowLevel](./set_changeallowlevel/)(int32_t) | Получает и задает уровень изменения привилегий документа. Аналогично настройкам Changes Allowed в Adobe Professional. 0: Нет. 1: Вставка, удаление и вращение страниц. 2: Заполнение полей формы и подпись существующих полей подписи. 3: Комментирование, заполнение полей формы и подпись существующих полей подписи. 4: Всё, кроме извлечения страниц. |
| [set_CopyAllowLevel](./set_copyallowlevel/)(int32_t) | Получает и задает уровень копирования привилегий документа. Аналогично настройкам разрешений в Adobe Professional. 0: Нет. 1: Включить доступ к тексту для устройств экранных читалок для слабовидящих. 2: Включить копирование текста, изображений и другого контента. |
| [set_PrintAllowLevel](./set_printallowlevel/)(int32_t) | Получает и задает уровень печати привилегий документа. Аналогично настройкам Printing Allowed в Adobe Professional. 0: Нет. 1: Низкое разрешение (150 dpi). 2: Высокое разрешение. |
## См. также

* Class [IComparable](../../system/icomparable/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
