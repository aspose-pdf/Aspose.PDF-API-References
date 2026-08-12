---
title: "is_pdfa_compliant"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanın PDF/A uyumlu olup olmadığını alır."
type: docs
url: /tr/rust-cpp/organize/is_pdfa_compliant/
---

_PDF-dökümanın PDF/A uyumlu olup olmadığını alır._

```rust
pub fn is_pdfa_compliant(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Dosya adıyla bir PDF-belgesi aç
    let pdf = Document::open("sample.pdf")?;

    // PDF-dökümanın PDF/A uyumluluk durumunu al
    if pdf.is_pdfa_compliant()? {
        println!("The document is PDF/A compliant.");
    } else {
        println!("The document is not PDF/A compliant.");
    }

    Ok(())
}

```