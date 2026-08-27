---
title: "IsSigned"
second_title: "Aspose.PDF für Go über C++"
description: "Signaturstatus des PDF-Dokuments abrufen."
type: docs
url: /de/go-cpp/security/issigned/
---

_Den Signaturstatus des PDF-Dokuments abrufen._

```go
func (document *Document) IsSigned() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is signed
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "fmt"

func main() {
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample_with_sign.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// IsSigned() ruft den Signaturstatus des PDF-Dokuments ab
	isSig, _ := pdf.IsSigned()
	if isSig {
		fmt.Println("IsSigned() is true")
	}
}
```
