---
title: "remove_pdfa_compliance"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Bir PDF-dokümandan PDF/A uyumluluğunu kaldır."
type: docs
url: /tr/rust-cpp/organize/remove_pdfa_compliance/
---

_PDF-dökümanından PDF/A uyumluluğunu kaldır._

```rust
pub fn remove_pdfa_compliance(&self) -> Result<(), PdfError>
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

    // Bir PDF-document'ten PDF/A uyumluluğunu kaldır
    pdf.remove_pdfa_compliance()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_remove_pdfa_compliance.pdf")?;

    Ok(())
}

```