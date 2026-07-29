---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF för Go via C++"
description: "Kontrollera om ett PDF-dokument är PDF/UA-kompatibelt."
type: docs
url: /sv/go-cpp/organize/ispdfuacompliant/
---

_Hämtar om ett PDF-dokument är PDF/UA-kompatibelt._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// IsPdfUaCompliant() hämtar PDF/UA-kompatibilitetsstatus för PDF-dokumentet
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
