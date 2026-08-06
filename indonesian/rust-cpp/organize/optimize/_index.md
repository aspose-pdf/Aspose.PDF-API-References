---
title: "optimize"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengoptimalkan konten dokumen PDF."
type: docs
url: /id/rust-cpp/organize/optimize/
---

_Mengoptimalkan konten dokumen PDF._

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
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Optimalkan konten dokumen PDF
    pdf.optimize()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_optimize.pdf")?;

    Ok(())
}

```