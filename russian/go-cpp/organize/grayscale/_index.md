---
title: "Оттенки серого"
second_title: "Aspose.PDF для Go через C++"
description: "Конвертировать PDF-документ в черно-белый."
type: docs
url: /ru/go-cpp/organize/grayscale/
---

_Преобразовать PDF-документ в черно-белый._

```go
func (document *Document) Grayscale() error
```

**Parameters**: 

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
	// Grayscale() преобразует PDF-документ в черно-белый
	err = pdf.Grayscale()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_Grayscale.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
