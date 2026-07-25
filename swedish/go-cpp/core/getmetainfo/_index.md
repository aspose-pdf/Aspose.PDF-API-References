---
title: "GetMetaInfo"
second_title: "Aspose.PDF för Go via C++"
description: "Hämta meta‑informationsvärde för PDF-dokumentet."
type: docs
url: /sv/go-cpp/core/getmetainfo/
---

_Hämta meta‑informationsvärde för PDF-dokumentet._

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
	// Open(filename string) öppnar ett PDF-dokument med filnamn
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() frigör allokerade resurser för PDF-dokument
	defer pdf.Close()
	// GetMetaInfo(key string) hämtar meta‑informationsvärde för PDF-dokumentet
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// Skriv ut
	fmt.Println("Author: ", value)
}
```
