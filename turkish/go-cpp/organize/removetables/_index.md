---
title: "RemoveTables"
second_title: "Aspose.PDF for Go via C++"
description: "PDF belgesinden tabloları kaldır."
type: docs
url: /tr/go-cpp/organize/removetables/
---

_PDF belgesinden tabloları kaldır._

```go
func (document *Document) RemoveTables() error
```

**Parameters**: 

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"

func main() {
	// Open(filename string) dosya adıyla bir PDF-belgesi açar
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() PDF-belgesi için ayrılan kaynakları serbest bırakır
	defer pdf.Close()
	// RemoveTables() PDF belgesinden tabloları kaldırır
	err = pdf.RemoveTables()
	if err != nil {
		log.Fatal(err)
	}
	// SaveAs(filename string) daha önce açılmış PDF belgesini yeni dosya adıyla kaydeder
	err = pdf.SaveAs("sample_RemoveTables.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
