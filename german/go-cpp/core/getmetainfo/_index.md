---
title: "GetMetaInfo"
second_title: "Aspose.PDF für Go über C++"
description: "Liefert den Meta-Informationswert des PDF-Dokuments."
type: docs
url: /de/go-cpp/core/getmetainfo/
---

_Liefert den Meta-Informationswert des PDF-Dokuments._

```go
func (document *Document) GetMetaInfo(key string) (string, error)
```

**Parameters**: 
  * **key** - key whose value to get

**Return**: 
  * **string** - value associated with the specified key
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
	// GetMetaInfo(key string) holt den Meta-Informationswert des PDF-Dokuments
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Author: ", value)
}
```
