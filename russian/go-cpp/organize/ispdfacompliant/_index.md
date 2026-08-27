---
title: "IsPdfaCompliant"
second_title: "Aspose.PDF для Go через C++"
description: "Определить, соответствует ли PDF-документ PDF/A."
type: docs
url: /ru/go-cpp/organize/ispdfacompliant/
---

_Get является PDF-документом, совместимым с PDF/A._

```go
func (document *Document) IsPdfaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/A compliant
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
	// IsPdfaCompliant() получает статус соответствия PDF/A PDF-документа
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
