---
title: "hakkında"
second_title: "Rust için C++ aracılığıyla Aspose.PDF"
description: "Aspose.PDF for Rust via C++ hakkında üst veri bilgilerini döndürür."
type: docs
url: /tr/rust-cpp/miscellaneous/about/
---

_Aspose.PDF for Rust via C++ hakkında üst veri bilgilerini döndürür._

```rust
pub fn about(&self) -> Result<ProductInfo, PdfError>
```

**Arguments**


**Returns**
  * **Ok(ProductInfo)** - if the operation succeeds
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Yeni bir PDF-document oluştur
    let pdf = Document::new()?;

    // Aspose.PDF for Go via C++ hakkında üst veri bilgilerini döndürür.
    let info = pdf.about()?;

    // Üst veri alanlarını yazdır
    println!("Product Info:");
    println!("  Product:      {}", info.product);
    println!("  Family:       {}", info.family);
    println!("  Version:      {}", info.version);
    println!("  ReleaseDate:  {}", info.release_date);
    println!("  Producer:     {}", info.producer);
    println!("  IsLicensed:   {}", info.is_licensed);

    Ok(())
}

```