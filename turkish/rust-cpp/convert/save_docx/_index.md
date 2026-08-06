---
title: "save_docx"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Açılmış PDF-dökümanını bir DOCX-dökümanına dönüştürür ve kaydeder."
type: docs
url: /tr/rust-cpp/convert/save_docx/
---

_Açılmış PDF-dökümanını bir DOCX-dökümanına dönüştürür ve kaydeder._

```rust
pub fn save_docx(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // Açılmış PDF-dökümanını DocX-dökümanına dönüştür ve kaydet
    pdf.save_docx("sample.docx")?;

    Ok(())
}

```