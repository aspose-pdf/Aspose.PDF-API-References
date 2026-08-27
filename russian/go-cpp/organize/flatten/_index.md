---
title: "Свести"
second_title: "Aspose.PDF для Go через C++"
description: "Свести PDF-документ."
type: docs
url: /ru/go-cpp/organize/flatten/
---

_Свести PDF-документ._

```go
func (document *Document) Flatten() error
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
	// Flatten() сводит PDF-документ
	err = pdf.Flatten()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) сохраняет ранее открытый PDF-документ с новым именем файла
	err = pdf.SaveAs("sample_Flatten.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
