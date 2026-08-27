---
title: "Aspose.PDF для Go через C++"
description: "Aspose.PDF для Go через C++"
keywords:  "Go, Golang, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /ru/go-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Go via C++ allows developers manipulate them PDF files directly in the Go.

# Types

## Document
Документ представляет PDF-документ.

```go
type Document struct {
}
```

# Functions

## Convert from PDF functions

| Функция | Описание |
| -------- | ----------- |
| [SaveDocX](./convert/savedocx/) | Преобразовать и сохранить ранее открытый PDF-документ как DocX-документ. |
| [SaveDoc](./convert/savedoc/) | Преобразовать и сохранить ранее открытый PDF-документ как Doc-документ. |
| [SaveXlsX](./convert/savexlsx/) | Преобразовать и сохранить ранее открытый PDF-документ как XlsX-документ. |
| [SaveTxt](./convert/savetxt/) | Преобразовать и сохранить ранее открытый PDF-документ как Txt-документ. |
| [SavePptX](./convert/savepptx/) | Преобразовать и сохранить ранее открытый PDF-документ как PptX-документ. |
| [SaveXps](./convert/savexps/) | Преобразовать и сохранить ранее открытый PDF-документ как Xps-документ. |
| [SaveTeX](./convert/savetex/) | Преобразовать и сохранить ранее открытый PDF-документ как TeX-документ. |
| [SaveEpub](./convert/saveepub/) | Преобразовать и сохранить ранее открытый PDF-документ как Epub-документ. |
| [SaveBooklet](./convert/savebooklet/) | Преобразовать и сохранить ранее открытый PDF-документ как PDF-документ брошюры. |
| [SaveNUp](./convert/savenup/) | Преобразовать и сохранить ранее открытый PDF-документ как N-Up PDF-документ. |
| [SaveMarkdown](./convert/savemarkdown/) | Преобразовать и сохранить ранее открытый PDF-документ как Markdown-документ. |
| [SaveTiff](./convert/savetiff/) | Преобразовать и сохранить ранее открытый PDF-документ как Tiff-документ. |
| [SaveDocXEnhanced](./convert/savedocxenhanced/) | Преобразовать и сохранить ранее открытый PDF-документ как DocX-документ с расширенным режимом распознавания (полностью редактируемые таблицы и абзацы). |
| [SaveSvgZip](./convert/savesvgzip/) | Преобразовать и сохранить ранее открытый PDF-документ как SVG-архив. |
| [ExportFdf](./convert/exportfdf/) | Экспортировать из ранее открытого PDF-документа с AcroForm в FDF-документ. |
| [ExportXfdf](./convert/exportxfdf/) | Экспортировать из ранее открытого PDF-документа с AcroForm в XFDF-документ. |
| [ExportXml](./convert/exportxml/) | Экспортировать из ранее открытого PDF-документа с AcroForm в XML-документ. |
| [PageToJpg](./convert/pagetojpg/) | Преобразовать и сохранить указанную страницу как Jpg-изображение. |
| [PageToPng](./convert/pagetopng/) | Преобразовать и сохранить указанную страницу как Png-изображение. |
| [PageToBmp](./convert/pagetobmp/) | Преобразовать и сохранить указанную страницу как Bmp-изображение. |
| [PageToTiff](./convert/pagetotiff/) | Преобразовать и сохранить указанную страницу как Tiff-изображение. |
| [PageToSvg](./convert/pagetosvg/) | Конвертировать и сохранить указанную страницу как Svg-image. |
| [PageToPdf](./convert/pagetopdf/) | Конвертировать и сохранить указанную страницу как Pdf. |
| [PageToDICOM](./convert/pagetodicom/) | Конвертировать и сохранить указанную страницу как DICOM-image. |


## Organize PDF functions

| Функция | Описание |
| -------- | ----------- |
| [Optimize](./organize/optimize/) | Оптимизировать содержимое PDF-документа. |
| [OptimizeResource](./organize/optimizeresource/) | Оптимизировать ресурсы PDF-документа. |
| [Grayscale](./organize/grayscale/) | Конвертировать PDF-документ в черно-белый. |
| [Rotate](./organize/rotate/) | Повернуть PDF-документ. |
| [SetBackground](./organize/setbackground/) | Установить цвет фона PDF-документа. |
| [Repair](./organize/repair/) | Восстановить PDF-документ. |
| [ReplaceText](./organize/replacetext/) | Заменить текст в PDF-документе. |
| [AddPageNum](./organize/addpagenum/) | Добавить номер страницы в PDF-документ. |
| [AddTextHeader](./organize/addtextheader/) | Добавить текст в заголовок PDF-документа. |
| [AddTextFooter](./organize/addtextfooter/) | Добавить текст в нижний колонтитул PDF-документа. |
| [Flatten](./organize/flatten/) | Свести PDF-документ. |
| [RemoveAnnotations](./organize/removeannotations/) | Удалить аннотации из PDF-документа. |
| [RemoveAttachments](./organize/removeattachments/) | Удалить вложения из PDF-документа. |
| [RemoveBlankPages](./organize/removeblankpages/) | Удалить пустые страницы из PDF-документа. |
| [RemoveBookmarks](./organize/removebookmarks/) | Удалить закладки из PDF-документа. |
| [RemoveHiddenText](./organize/removehiddentext/) | Удалить скрытый текст из PDF-документа. |
| [RemoveImages](./organize/removeimages/) | Удалить изображения из PDF-документа. |
| [RemoveJavaScripts](./organize/removejavascripts/) | Удалить JavaScript из PDF-документа. |
| [RemoveTables](./organize/removetables/) | Удалить таблицы из PDF-документа. |
| [RemoveWatermarks](./organize/removewatermarks/) | Удалить водяные знаки из PDF-документа. |
| [AddWatermark](./organize/addwatermark/) | Добавить водяной знак в PDF-документ. |
| [EmbedFonts](./organize/embedfonts/) | Встроить шрифты в PDF-документ. |
| [UnembedFonts](./organize/unembedfonts/) | Удалить встраивание шрифтов в PDF-документе. |
| [OptimizeFileSize](./organize/optimizefilesize/) | Оптимизировать размер PDF-документа с качеством сжатия изображений. |
| [RemoveTextHeaders](./organize/removetextheaders/) | Удалить текстовые заголовки из PDF-документа. |
| [RemoveTextFooters](./organize/removetextfooters/) | Удалить текстовые колонтитулы из PDF-документа. |
| [Crop](./organize/crop/) | Обрезать страницы PDF-документа. |
| [ReplaceFont](./organize/replacefont/) | Заменить шрифт в PDF-документе. |
| [Convert](./organize/convert/) | Преобразовать PDF-документ в PDF-документ с указанным форматом PDF. |
| [Validate](./organize/validate/) | Проверить PDF-документ на соответствие формату PDF. |
| [RemovePdfaCompliance](./organize/removepdfacompliance/) | Удалить соответствие PDF/A из PDF-документа. |
| [RemovePdfUaCompliance](./organize/removepdfuacompliance/) | Удалить соответствие PDF/UA из PDF-документа. |
| [IsPdfaCompliant](./organize/ispdfacompliant/) | Определить, соответствует ли PDF-документ PDF/A. |
| [IsPdfUaCompliant](./organize/ispdfuacompliant/) | Определить, соответствует ли PDF-документ PDF/UA. |
| [PageRotate](./organize/pagerotate/) | Повернуть страницу. |
| [PageSetSize](./organize/pagesetsize/) | Установить размер страницы. |
| [PageGrayscale](./organize/pagegrayscale/) | Преобразовать страницу в черно-белую. |
| [PageAddText](./organize/pageaddtext/) | Добавить текст на страницу. |
| [PageReplaceText](./organize/pagereplacetext/) | Заменить текст на странице. |
| [PageAddPageNum](./organize/pageaddpagenum/) | Добавить номер страницы на страницу. |
| [PageAddTextHeader](./organize/pageaddtextheader/) | Добавить текст в заголовок страницы. |
| [PageAddTextFooter](./organize/pageaddtextfooter/) | Добавить текст в нижний колонтитул страницы. |
| [PageRemoveAnnotations](./organize/pageremoveannotations/) | Удалить аннотации на странице. |
| [PageRemoveHiddenText](./organize/pageremovehiddentext/) | Удалить скрытый текст на странице. |
| [PageRemoveImages](./organize/pageremoveimages/) | Удалить изображения на странице. |
| [PageRemoveTables](./organize/pageremovetables/) | Удалить таблицы на странице. |
| [PageRemoveWatermarks](./organize/pageremovewatermarks/) | Удалить водяные знаки на странице. |
| [PageAddWatermark](./organize/pageaddwatermark/) | Добавить водяной знак на страницу. |
| [PageRemoveTextHeaders](./organize/pageremovetextheaders/) | Удалить текстовые заголовки на странице. |
| [PageRemoveTextFooters](./organize/pageremovetextfooters/) | Удалить текстовые колонтитулы на странице. |
| [PageCrop](./organize/pagecrop/) | Обрезать страницу. |
| [PageReplaceFont](./organize/pagereplacefont/) | Заменить шрифт на странице. |
| [PageMergeLayers](./organize/pagemergelayers/) | Объединить все слои на странице в один слой с указанным новым именем слоя. |
| [PageLayers](./organize/pagelayers/) | Получает имена слоёв на странице. |


## Core PDF functions

| Функция | Описание |
| -------- | ----------- |
| [New](./core/new/) | Создать новый PDF-document. |
| [Open](./core/open/) | Открыть PDF-document с именем файла. |
| [Save](./core/save/) | Сохранить ранее открытый PDF-document. |
| [SaveAs](./core/saveas/) | Сохранить ранее открытый PDF-document с новым именем файла. |
| [Close](./core/close/) | Освободить выделенные ресурсы для PDF-document. |
| [SetLicense](./core/setlicense/) | Установить лицензию с помощью имени файла. |
| [ExtractText](./core/extracttext/) | Вернуть содержимое PDF-document в виде простого текста. |
| [WordCount](./core/wordcount/) | Вернуть количество слов в PDF-document. |
| [CharacterCount](./core/charactercount/) | Вернуть количество символов в PDF-document. |
| [Append](./core/append/) | Добавить страницы из другого PDF-document. |
| [AppendPages](./core/appendpages/) | Добавить выбранные страницы из другого PDF-document. |
| [MergeDocuments](./core/mergedocuments/) | Создать новый PDF-document, объединив предоставленные PDF-documents. |
| [SplitDocument](./core/splitdocument/) | Создать несколько новых PDF-documents, извлекая страницы из исходного PDF-document. |
| [Split](./core/split/) | Создать несколько новых PDF-documents, извлекая страницы из текущего PDF-document. |
| [SplitAtPage](./core/splitatpage/) | Разделить PDF-document на два новых PDF-documents. |
| [SplitAt](./core/splitat/) | Разделить текущий PDF-document на два новых PDF-documents. |
| [Bytes](./core/bytes/) | Вернуть содержимое PDF-document в виде среза байтов. |
| [GetMetaInfo](./core/getmetainfo/) | Получить значение мета‑информации PDF-document.. |
| [SetMetaInfo](./core/setmetainfo/) | Установить значение метаинформации PDF-документа.. |
| [ClearMetaInfo](./core/clearmetainfo/) | Очистить все значения метаинформации PDF-документа.. |
| [IsLinearized](./core/islinearized/) | Получить значение, указывающее, линейзирован ли документ. |
| [PageAdd](./core/pageadd/) | Добавить новую страницу в PDF-документ. |
| [PageInsert](./core/pageinsert/) | Вставить новую страницу в указанной позиции PDF-документа. |
| [PageDelete](./core/pagedelete/) | Удалить указанную страницу из PDF-документа. |
| [PageCount](./core/pagecount/) | Вернуть количество страниц в PDF-документе. |
| [PageWordCount](./core/pagewordcount/) | Вернуть количество слов на указанной странице PDF-документа. |
| [PageCharacterCount](./core/pagecharactercount/) | Вернуть количество символов на указанной странице PDF-документа. |
| [PageIsBlank](./core/pageisblank/) | Вернуть, является ли страница пустой в PDF-документе. |


## Security

| Функция | Описание |
| -------- | ----------- |
| [OpenWithPassword](./security/openwithpassword/) | Открыть защищённый паролем PDF-документ. |
| [Encrypt](./security/encrypt/) | Зашифровать PDF-документ. |
| [Decrypt](./security/decrypt/) | Расшифровать PDF-документ. |
| [SetPermissions](./security/setpermissions/) | Установить разрешения для PDF-документа. |
| [GetPermissions](./security/getpermissions/) | Получить текущие разрешения PDF-документа. |
| [IsEncrypted](./security/isencrypted/) | Получить статус шифрования PDF-документа. |
| [SignPKCS7](./security/signpkcs7/) | Подписать PDF-документ с использованием цифровых подписей PKCS#7. |
| [SignPKCS7Detached](./security/signpkcs7detached/) | Подписать PDF-документ с использованием откреплённых цифровых подписей PKCS#7. |
| [IsSigned](./security/issigned/) | Получить статус подписи PDF-документа. |
| [RemoveSigns](./security/removesigns/) | Удалить подписи из PDF-документа. |


## Miscellaneous

| Функция | Описание |
| -------- | ----------- |
| [About](./miscellaneous/about/) | Вернуть информацию о метаданных Aspose.PDF for Go через C++. |


# Types secondary

## ProductInfo contains metadata about the Aspose.PDF for Go via C++.
```go
type ProductInfo struct {
	Product     string `json:"product"`     // Name
	Family      string `json:"family"`      // Family (e.g., "Aspose.PDF")
	Version     string `json:"version"`     // Version
	ReleaseDate string `json:"releasedate"` // Release date in ISO format (YYYY-MM-DD)
	Producer    string `json:"producer"`    // Producer
	IsLicensed  bool   `json:"islicensed"`  // License status (true if licensed)
}
```


# Constants

## Enumeration of possible rotation values.
```go
const (
    RotationNone  int32 = 0 // Non-rotated.
    RotationOn90  int32 = 1 // Rotated on 90 degrees clockwise.
    RotationOn180 int32 = 2 // Rotated on 180 degrees.
    RotationOn270 int32 = 3 // Rotated on 270 degrees clockwise.
    RotationOn360 int32 = 4 // Rotated on 360 degrees clockwise.
)
```

## Enumeration of possible page size values.
```go
const (
    PageSizeA0         int32 = 0  // A0 size.
    PageSizeA1         int32 = 1  // A1 size.
    PageSizeA2         int32 = 2  // A2 size.
    PageSizeA3         int32 = 3  // A3 size.
    PageSizeA4         int32 = 4  // A4 size.
    PageSizeA5         int32 = 5  // A5 size.
    PageSizeA6         int32 = 6  // A6 size.
    PageSizeB5         int32 = 7  // B5 size.
    PageSizePageLetter int32 = 8  // PageLetter size.
    PageSizePageLegal  int32 = 9  // PageLegal size.
    PageSizePageLedger int32 = 10 // PageLedger size.
    PageSizeP11x17     int32 = 11 // P11x17 size.
)
```

## Enumeration of possible crypto algorithms.
```go
type CryptoAlgorithm int32
const (
	RC4x40  CryptoAlgorithm = 0 // RC4 with key length 40.
	RC4x128 CryptoAlgorithm = 1 // RC4 with key length 128.
	AESx128 CryptoAlgorithm = 2 // AES with key length 128.
	AESx256 CryptoAlgorithm = 3 // AES with key length 256.
)
```

## Enumeration of possible PDF formats.
```go
type PdfFormat int32
const (
	PDF_A_1A      PdfFormat = iota // Pdf/A-1a format.
	PDF_A_1B                       // Pdf/A-1b format.
	PDF_A_2A                       // Pdf/A-2a format.
	PDF_A_3A                       // Pdf/A-3a format.
	PDF_A_2B                       // Pdf/A-2b format.
	PDF_A_2U                       // Pdf/A-2u format.
	PDF_A_3B                       // Pdf/A-3b format.
	PDF_A_3U                       // Pdf/A-3u format.
	V_1_0                          // Adobe version 1.0.
	V_1_1                          // Adobe version 1.1.
	V_1_2                          // Adobe version 1.2.
	V_1_3                          // Adobe version 1.3.
	V_1_4                          // Adobe version 1.4.
	V_1_5                          // Adobe version 1.5.
	V_1_6                          // Adobe version 1.6.
	V_1_7                          // Adobe version 1.7.
	V_2_0                          // ISO Standard PDF 2.0.
	PDF_UA_1                       // PDF/UA-1 format.
	PDF_X_1A_2001                  // PDF/X-1a-2001 format.
	PDF_X_1A                       // PDF/X-1a format.
	PDF_X_3                        // PDF/X-3 format.
	ZUGFeRD                        // ZUGFeRD format.
	PDF_A_4                        // PDF/A-4 format.
	PDF_A_4E                       // PDF/A-4e format.
	PDF_A_4F                       // PDF/A-4f format.
	PDF_X_4                        // PDF/X-4 format.
	PDF_E_1                        // PDF/E-1 (PDF 1.6) format.
)
```

## Enumeration of possible conversion errors action.
```go
type ConvertErrorAction int32
const (
	Delete ConvertErrorAction = iota // Delete convert errors.
	None                             // Do nothing with convert errors.
)
```

## Bitflag set representing PDF permission capabilities.
```go
type Permissions int32
const (
    PrintDocument                  Permissions = 1 << 2  // 4
    ModifyContent                  Permissions = 1 << 3  // 8
    ExtractContent                 Permissions = 1 << 4  // 16
    ModifyTextAnnotations          Permissions = 1 << 5  // 32
    FillForm                       Permissions = 1 << 8  // 256
    ExtractContentWithDisabilities Permissions = 1 << 9  // 512
    AssembleDocument               Permissions = 1 << 10 // 1024
    PrintingQuality                Permissions = 1 << 11 // 2048
)
```
