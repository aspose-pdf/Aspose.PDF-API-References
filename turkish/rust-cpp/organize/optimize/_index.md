---
title: "optimize"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "PDF-döküman içeriğini optimize eder."
type: docs
url: /tr/rust-cpp/organize/optimize/
---

_PDF-döküman içeriğini optimize eder._

```rust
pub fn optimize(&self) -> Result<(), PdfError>
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

    // PDF-döküman içeriğini optimize et
    pdf.optimize()?;

    // Daha önce açılmış PDF belgesini yeni dosya adıyla kaydet
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```