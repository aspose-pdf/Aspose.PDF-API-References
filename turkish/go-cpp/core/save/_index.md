---
title: "Kaydet"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dökümanı kaydet."
type: docs
url: /tr/go-cpp/core/save/
---

_Daha önce açılmış PDF-document'i kaydet._

```go
func (document *Document) Save() error
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
	// Save() daha önce açılmış PDF belgesini kaydeder
	err = pdf.Save()
	if err != nil {
		log.Fatal(err)
	}
}
```
