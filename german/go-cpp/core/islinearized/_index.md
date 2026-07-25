---
title: "IsLinearized"
second_title: "Aspose.PDF für Go über C++"
description: "Einen Wert erhalten, der angibt, ob das Dokument linearisiert ist."
type: docs
url: /de/go-cpp/core/islinearized/
---

_Gibt einen Wert zurück, der angibt, ob das Dokument linearisiert ist._

```go
func (document *Document) IsLinearized() (bool, error)
```

**Parameters**: 

**Return**: 
  * **bool** - the document is linearized
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
	// IsLinearized() gibt einen Wert zurück, der angibt, ob das Dokument linearisiert ist
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
