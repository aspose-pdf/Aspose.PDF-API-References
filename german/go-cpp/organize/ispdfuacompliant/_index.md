---
title: "IsPdfUaCompliant"
second_title: "Aspose.PDF für Go über C++"
description: "Ermitteln, ob ein PDF-Dokument PDF/UA-konform ist."
type: docs
url: /de/go-cpp/organize/ispdfuacompliant/
---

_Ermittelt, ob ein PDF-Dokument PDF/UA konform ist._

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
	// Open(filename string) öffnet ein PDF-document mit Dateiname
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() gibt zugewiesene Ressourcen für PDF-document frei
	defer pdf.Close()
	// IsPdfUaCompliant() ermittelt den PDF/UA‑Konformitätsstatus des PDF-Dokuments
	isPdfua, _ := pdf.IsPdfUaCompliant()
	if isPdfua {
		fmt.Println("IsPdfUaCompliant() is true")
	} else {
		fmt.Println("IsPdfUaCompliant() is false")
	}
}
```
