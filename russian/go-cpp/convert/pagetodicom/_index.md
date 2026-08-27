---
title: "PageToDICOM"
second_title: "Aspose.PDF для Go через C++"
description: "Конвертировать и сохранить указанную страницу как DICOM-image."
type: docs
url: /ru/go-cpp/convert/pagetodicom/
---

_Преобразовать и сохранить указанную страницу как DICOM-изображение._

```go
func (document *Document) PageToDICOM(num int32, resolution_dpi int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
  * **resolution_dpi** - resolution in DPI of the resulting file
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// PageToDICOM(num int32, resolution_dpi int32, filename string) сохраняет указанную страницу как файл DICOM-изображения
	err = pdf.PageToDICOM(1, 100, "sample_page1.dcm")
	if err != nil {
		log.Fatal(err)
	}
}
```
