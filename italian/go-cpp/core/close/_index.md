---
title: "Close"
second_title: "Aspose.PDF per Go via C++"
description: "Rilascia le risorse allocate per il documento PDF."
type: docs
url: /it/go-cpp/core/close/
---

_Rilascia le risorse allocate per il documento PDF._

```go
func (document *Document) Close() error
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
	// New crea un nuovo PDF-document
	pdf, err := asposepdf.New()
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// SaveAs(filename string) salva il PDF-document precedentemente aperto con un nuovo nome file
	err = pdf.SaveAs("sample_New_SaveAs.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
