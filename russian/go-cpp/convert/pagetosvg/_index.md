---
title: "PageToSvg"
second_title: "Aspose.PDF для Go через C++"
description: "Конвертировать и сохранить указанную страницу как Svg-image."
type: docs
url: /ru/go-cpp/convert/pagetosvg/
---

_Преобразовать и сохранить указанную страницу как Svg-изображение._

```go
func (document *Document) PageToSvg(num int32, filename string) error
```

**Parameters**: 
  * **num** - page number of the PDF-document
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
	// PageToSvg(num int32, filename string) сохраняет указанную страницу как файл изображения Svg
	err = pdf.PageToSvg(1, "sample_page1.svg")
	if err != nil {
		log.Fatal(err)
	}
}
```
