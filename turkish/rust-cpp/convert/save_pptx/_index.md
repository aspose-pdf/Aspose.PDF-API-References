---
title: "save_pptx"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Açılmış PDF-dökümanını bir PPTX-dökümanına dönüştürür ve kaydeder."
type: docs
url: /tr/rust-cpp/convert/save_pptx/
---

_Açılmış PDF-dökümanını bir PPTX-dökümanına dönüştürür ve kaydeder._

```rust
pub fn save_pptx(&self, filename: &str) -> Result<(), PdfError>
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

    // Açılmış PDF-dökümanını PptX-dökümanına dönüştür ve kaydet
    pdf.save_pptx("sample.pptx")?;

    Ok(())
}

```