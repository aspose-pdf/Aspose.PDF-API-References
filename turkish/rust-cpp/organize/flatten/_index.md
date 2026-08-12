---
title: "flatten"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-belgesini düzleştirir."
type: docs
url: /tr/rust-cpp/organize/flatten/
---

_PDF-belgesini düzleştirir._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
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

    // PDF belgesinin içeriğini düz metin olarak döndür
    let txt = pdf.extract_text()?;

    // Çıkarılan metni yazdır
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```