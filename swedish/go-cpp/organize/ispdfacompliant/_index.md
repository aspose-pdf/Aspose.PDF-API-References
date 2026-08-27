---
title: "IsPdfaCompliant"
second_title: "Aspose.PDF för Go via C++"
description: "Kontrollera om ett PDF-dokument är PDF/A-kompatibelt."
type: docs
url: /sv/go-cpp/organize/ispdfacompliant/
---

_Get är ett PDF-dokument PDF/A-kompatibelt._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// IsPdfaCompliant() hämtar PDF/A-kompatibilitetsstatus för PDF-dokument
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
