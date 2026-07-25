---
title: "IsLinearized"
second_title: "Aspose.PDF för Go via C++"
description: "Hämta ett värde som indikerar om dokumentet är lineariserat."
type: docs
url: /sv/go-cpp/core/islinearized/
---

_Hämta ett värde som indikerar om dokumentet är lineariserat._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// IsLinearized() hämtar ett värde som indikerar om dokumentet är lineariserat
	isLinearized, _ := pdf.IsLinearized()
	if isLinearized {
		fmt.Println("IsLinearized() is true")
	} else {
		fmt.Println("IsLinearized() is false")
	}
}
```
