---
title: "PageToBmp"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить указанную страницу как Bmp-изображение."
type: docs
url: /ru/go-cpp/convert/pagetobmp/
---

_Преобразовать и сохранить указанную страницу как Bmp-изображение._

```go
func (document *Document) PageToBmp(num int32, resolution_dpi int32, filename string) error
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
	// PageToBmp(num int32, resolution_dpi int32, filename string) сохраняет указанную страницу как файл Bmp-изображения
	err = pdf.PageToBmp(1, 100, "sample_page1.bmp")
	if err != nil {
		log.Fatal(err)
	}
}
```
