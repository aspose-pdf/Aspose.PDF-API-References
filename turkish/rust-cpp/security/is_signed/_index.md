---
title: "is_signed"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-dökümanının imzalı durumunu al."
type: docs
url: /tr/rust-cpp/security/is_signed/
---

_PDF-document'in imzalı durumunu al._

```rust
pub fn is_signed(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // "sample_with_sign.pdf" adlı bir PDF-document aç
    let pdf = Document::open("sample_with_sign.pdf")?;

    // PDF-document'in imzalı durumunu al
    if pdf.is_signed()? {
        println!("The document is signed.");
    }

    Ok(())
}

```