---
title: "PageGrayscale"
second_title: "Aspose.PDF для Go через C++"
description: "Преобразовать страницу в черно-белую."
type: docs
url: /ru/go-cpp/organize/pagegrayscale/
---

_Преобразовать страницу в черно‑белый режим._

```go
func (document *Document) PageGrayscale(num int32) error
```

**Parameters**: 
  * **num** - page number of the PDF-document

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
	// PageGrayscale(num int32) преобразует страницу в черно‑белый режим
	err = pdf.PageGrayscale(1)
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_page1_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
