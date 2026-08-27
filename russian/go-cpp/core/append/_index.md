---
title: "Append"
second_title: "Aspose.PDF для Go через C++"
description: "Добавить страницы из другого PDF-document."
type: docs
url: /ru/go-cpp/core/append/
---

_Добавить страницы из другого PDF-документа._

```go
func (document *Document) Append(anotherdocument *Document) error
```

**Parameters**: 
  * **anotherdocument** - reference to PDF-document instance

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

	// Open(filename string) открывает другой PDF-документ с именем файла
	anotherpdf, err := asposepdf.Open("sample1page.pdf")
	if err != nil {
		log.Fatal(err)
	}

	// Close() освобождает выделенные ресурсы для PDF-документа
	defer anotherpdf.Close()

	// Append(anotherdocument *Document) добавляет страницы из другого PDF-документа.
	err = pdf.Append(anotherpdf)
	if err != nil {
		log.Fatal(err)
	}

	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_Append.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
