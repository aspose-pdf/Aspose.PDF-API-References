---
title: "optimize_file_size"
second_title: "Aspose.PDF untuk Rust via C++"
description: "Mengoptimalkan ukuran dokumen PDF dengan kualitas kompresi gambar."
type: docs
url: /id/rust-cpp/organize/optimize_file_size/
---

_Mengoptimalkan ukuran dokumen PDF dengan kualitas kompresi gambar._

```rust
pub fn optimize_file_size(&self, image_quality: i32) -> Result<(), PdfError>
```

**Arguments**
  * **image_quality** - the image compression quality

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Buka dokumen PDF dengan nama file
    let pdf = Document::open("sample.pdf")?;

    // Optimalkan ukuran dokumen PDF dengan kualitas kompresi gambar
    pdf.optimize_file_size(50)?;

    // Simpan dokumen PDF yang sebelumnya dibuka dengan nama file baru
    pdf.save_as("sample_optimize_file_size.pdf")?;

    Ok(())
}

```