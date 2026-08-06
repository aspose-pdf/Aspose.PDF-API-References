---
title: "remove_watermarks"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Menghapus watermark dari dokumen PDF."
type: docs
url: /id/rust-cpp/organize/remove_watermarks/
---

_Menghapus watermark dari dokumen PDF._

```rust
pub fn remove_watermarks(&self) -> Result<(), PdfError>
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

    // Hapus watermark dari dokumen PDF
    pdf.remove_watermarks()?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_remove_watermarks.pdf")?;

    Ok(())
}

```