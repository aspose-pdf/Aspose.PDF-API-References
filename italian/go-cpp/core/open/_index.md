---
title: "Open"
second_title: "Aspose.PDF per Go via C++"
description: "Apri un documento PDF con nome file."
type: docs
url: /it/go-cpp/core/open/
---

_Apri un PDF-document con nome file._

```go
func Open(filename string) (*Document, error)
```

**Parameters**: 
  * **\*Document** - pointer to document
  * **filename** - full file name of the PDF-document

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
	// Save() salva il PDF-document precedentemente aperto
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
