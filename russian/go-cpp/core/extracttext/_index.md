---
title: "ExtractText"
second_title: "Aspose.PDF для Go через C++"
description: "Вернуть содержимое PDF-document в виде простого текста."
type: docs
url: /ru/go-cpp/core/extracttext/
---

_Верните содержимое PDF-документа в виде обычного текста._

```go
func (document *Document) ExtractText() (string, error)
```

**Parameters**: 

**Return**: 
  * **string** - PDF-document contents as plain text
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) открывает PDF-документ с именем файла
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() освобождает выделенные ресурсы для PDF-документа
	defer pdf.Close()
	// ExtractText() возвращает содержимое PDF-документа в виде обычного текста
	txt, err := pdf.ExtractText()
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Extracted text:\n", txt)
}
```
