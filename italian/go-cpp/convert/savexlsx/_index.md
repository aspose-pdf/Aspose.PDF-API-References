---
title: "SaveXlsX"
second_title: "Aspose.PDF per Go via C++"
description: "Converti e salva il PDF-document precedentemente aperto come XlsX-document."
type: docs
url: /it/go-cpp/convert/savexlsx/
---

_Converti e salva il PDF-document precedentemente aperto come XlsX-document._

```go
func (document *Document) SaveXlsX(filename string) error
```

**Parameters**: 
  * **filename** - new filename

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// SaveXlsX(filename string) salva il PDF-document precedentemente aperto come XlsX-document con filename
	err = pdf.SaveXlsX("sample.xlsx")
	if err != nil {
		log.Fatal(err)
	}
}
```
