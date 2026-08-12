---
title: "SaveNUp"
second_title: "Aspose.PDF for Go via C++"
description: "Önceden açılmış PDF-dokümanını N-Up PDF-dokümanı olarak dönüştür ve kaydet."
type: docs
url: /tr/go-cpp/convert/savenup/
---

_Daha önce açılmış PDF-dokümanı N-Up PDF-dokümanı olarak dönüştür ve kaydet._

```go
func (document *Document) SaveNUp(filename string, columns int32, rows int32) error
```

**Parameters**: 
  * **filename** - new filename
  * **columns** - number of columns
  * **rows** - number of rows

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
	// SaveNUp(filename string, columns int32, rows int32) daha önce açılmış PDF-dokümanı N-Up PDF-dokümanı olarak dosya adıyla kaydeder
	err = pdf.SaveNUp("sample_NUp.pdf", 2, 2)
	if err != nil {
		log.Fatal(err)
	}
}
```
