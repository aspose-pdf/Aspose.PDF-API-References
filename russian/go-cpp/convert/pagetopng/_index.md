---
title: "PageToPng"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать и сохранить указанную страницу как Png-изображение."
type: docs
url: /ru/go-cpp/convert/pagetopng/
---

_Конвертировать и сохранить указанную страницу как Png-image._

```go
func (document *Document) PageToPng(num int32, resolution_dpi int32, filename string) error
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
	// PageToPng(num int32, resolution_dpi int32, filename string) сохраняет указанную страницу как файл Png-image
	err = pdf.PageToPng(1, 100, "sample_page1.png")
	if err != nil {
		log.Fatal(err)
	}
}
```
