---
title: "is_pdfua_compliant"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanın PDF/UA uyumlu olduğunu alır."
type: docs
url: /tr/rust-cpp/organize/is_pdfua_compliant/
---

_PDF-dökümanın PDF/UA uyumlu olduğunu alır._

```rust
pub fn is_pdfua_compliant(&self) -> Result<bool, PdfError>
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

    // PDF-dökümanın PDF/UA uyum durumunu al
    if pdf.is_pdfua_compliant()? {
        println!("The document is PDF/UA compliant.");
    } else {
        println!("The document is not PDF/UA compliant.");
    }

    Ok(())
}

```