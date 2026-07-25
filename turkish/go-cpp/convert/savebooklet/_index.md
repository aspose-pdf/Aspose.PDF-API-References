---
title: "SaveBooklet"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını kitapçık PDF-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savebooklet/
---

_Önceden açılmış PDF-belgesini kitapçık PDF-belgesi olarak dönüştür ve kaydet._

```go
func (document *Document) SaveBooklet(filename string) error
```

**Parameters**: 
  * **filename** - new filename

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
	// SaveBooklet(filename string) önceden açılmış PDF-belgesini dosya adıyla kitapçık PDF-belgesi olarak kaydeder
	err = pdf.SaveBooklet("sample_Booklet.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
