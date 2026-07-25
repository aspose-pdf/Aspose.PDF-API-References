---
title: "SaveDoc"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını Doc-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savedoc/
---

_Daha önce açılmış PDF-dokümanı Doc-dokümanı olarak dönüştür ve kaydet._

```go
func (document *Document) SaveDoc(filename string) error
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
	// SaveDoc(filename string) daha önce açılmış PDF-dokümanı Doc-dokümanı olarak dosya adıyla kaydeder
	err = pdf.SaveDoc("sample.doc")
	if err != nil {
		log.Fatal(err)
	}
}
```
