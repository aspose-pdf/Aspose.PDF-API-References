---
title: "GetMetaInfo"
second_title: "Aspose.PDF untuk Go via C++"
description: "Dapatkan nilai informasi meta dari dokumen PDF."
type: docs
url: /id/go-cpp/core/getmetainfo/
---

_Dapatkan nilai informasi meta dari dokumen PDF._

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
	// Open(filename string) membuka PDF-dokumen dengan nama file
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() melepaskan sumber daya yang dialokasikan untuk PDF-dokumen
	defer pdf.Close()
	// GetMetaInfo(key string) mendapatkan nilai informasi meta dari dokumen PDF
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Author: ", value)
}
```
