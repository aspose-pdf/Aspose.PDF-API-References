---
title: "IsPdfaCompliant"
second_title: "Aspose.PDF für Go über C++"
description: "Ermitteln, ob ein PDF-Dokument PDF/A-konform ist."
type: docs
url: /de/go-cpp/organize/ispdfacompliant/
---

_Get ist ein PDF-Dokument PDF/A konform._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// IsPdfaCompliant() ermittelt den PDF/A-Konformitätsstatus des PDF-Dokuments
	isPdfa, _ := pdf.IsPdfaCompliant()
	if isPdfa {
		fmt.Println("IsPdfaCompliant() is true")
	} else {
		fmt.Println("IsPdfaCompliant() is false")
	}
}
```
