---
title: "grayscale"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-belgesini siyah beyaza dönüştürür."
type: docs
url: /tr/rust-cpp/organize/grayscale/
---

_PDF-belgesini siyah beyaza dönüştürür._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // PDF-belgesini siyah beyaza dönüştür
    pdf.grayscale()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```