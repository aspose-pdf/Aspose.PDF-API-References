---
title: "SignPKCS7"
second_title: Aspose.PDF for Go via C++
description: "Sign a PDF-document using PKCS#7 digital signatures."
type: docs
url: /go-cpp/security/signpkcs7/
---

_Sign a PDF-document using PKCS#7 digital signatures._

```go
func (document *Document) SignPKCS7(num int32, signData []byte, pswSign string, setXIndent, setYIndent, setHeight, setWidth int32, reason, contact, location string, isVisible bool, appearanceData []byte, filename string) error
```

**Parameters**: 
  * **num** - the page number of the PDF-document
  * **signData** - the raw bytes of the signature (PKCS#7 specification in Internet RFC 2315)
  * **pswSign** - the password of the signature
  * **setXIndent** - the x indent of the signature
  * **setYIndent** - the y indent of the signature
  * **setHeight** - the height of the signature
  * **setWidth** - the width of the signature
  * **reason** - the reason of a signature
  * **contact** - the contact of a signature
  * **location** -  the location of a signature
  * **isVisible** - the visiblity of signature
  * **appearanceData** - the raw bytes of the graphic appearance for the signature
  * **filename** - the new filename, with signature

**Return**: 
  * **error** - contains an error or nil if absent


**Example**:
```go
package main

import "github.com/aspose-pdf/aspose-pdf-go-cpp"
import "log"
import "os"

func main() {
	cert, _ := os.ReadFile("sign.pfx")
	img, _ := os.ReadFile("sign.png")

	// Open(filename string) opens a PDF-document with filename
	pdf, err := asposepdf.Open("sample.pdf")
	if err != nil {
		log.Fatal(err)
	}
	// Close() releases allocated resources for PDF-document
	defer pdf.Close()

	// SignPKCS7 signs a PDF-document using PKCS#7 digital signatures
	err = pdf.SignPKCS7(1, cert, "Pa$$w0rd2023", 100, 100, 70, 100, "Reason", "Contact", "Location", true, img, "sample_SignPKCS7.pdf")
	if err != nil {
		log.Fatal(err)
	}
}
```
