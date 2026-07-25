---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF per Go via C++"
description: "Verifica se un PDF-document è conforme a PDF/UA."
type: docs
url: /it/go-cpp/organize/ispdfuacompliant/
---

_Restituisce se un documento PDF è conforme a PDF/UA._

```go
func (document *Document) IsPdfUaCompliant() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is PDF/UA compliant
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) apre un PDF-document con filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() rilascia le risorse allocate per il PDF-document
	defer pdf.Close()
	// IsPdfUaCompliant() restituisce lo stato di conformità PDF/UA del documento PDF
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
