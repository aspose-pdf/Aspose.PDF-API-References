---
title: "GetMetaInfo"
second_title: "Aspose.PDF pour Go via C++"
description: "Obtenir la valeur de l'information méta du PDF-document."
type: docs
url: /fr/go-cpp/core/getmetainfo/
---

_Obtenir la valeur de l'information méta du PDF-document._

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
	// Open(filename string) ouvre un PDF-document avec filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() libère les ressources allouées pour le PDF-document
	defer pdf.Close()
	// GetMetaInfo(key string) obtient la valeur de l'information méta du PDF-document
	value, err := pdf.GetMetaInfo("Author")
	if err != nil {
		log.Fatal(err)
	}
	// Print
	fmt.Println("Author: ", value)
}
```
