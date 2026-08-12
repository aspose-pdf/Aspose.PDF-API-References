---
title: "repair"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanı onarır."
type: docs
url: /tr/rust-cpp/organize/repair/
---

_PDF-dosyayı onarır._

```rust
pub fn repair(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dosyayı Onar
    pdf.repair()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_repair.pdf")?;

    Ok(())
}

```