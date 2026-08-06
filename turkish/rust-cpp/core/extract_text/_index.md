---
title: "extract_text"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF belgesinin içeriğini düz metin olarak döndürür."
type: docs
url: /tr/rust-cpp/core/extract_text/
---

_PDF belgesinin içeriğini düz metin olarak döndürür._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
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