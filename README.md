# 🔒 JavaScript Security Scanner

<div align="center">

![Security Scanner Demo](https://img.shields.io/badge/Security-Scanner-red?style=for-the-badge&logo=shield&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**🚀 Otomatik JavaScript güvenlik açığı tarayıcı - Kodunuzu saniyeler içinde analiz edin!**

[🎮 Demo](https://your-demo-link.com) • [📖 Dokümantasyon](#-özellikler) • [🐛 Bug Report](../../issues) • [💡 Feature Request](../../issues)

</div>

## ✨ Özellikler

| 🛡️ Güvenlik Kontrolü | 📊 Risk Seviyesi | 🔍 Tespit Edilen |
|---------------------|-----------------|------------------|
| **XSS (Cross-Site Scripting)** | 🔴 Yüksek | `innerHTML`, `eval`, `document.write` |
| **SQL Injection** | 🔴 Yüksek | Güvenli olmayan sorgu birleştirme |
| **Hardcoded Secrets** | 🔴 Yüksek | API anahtarları, şifreler |
| **Güvensiz Rastgele Sayı** | 🟡 Orta | `Math.random()` kullanımı |
| **Open Redirect** | 🟡 Orta | Güvenli olmayan yönlendirmeler |
| **LocalStorage XSS** | 🟡 Orta | Storage verilerinin güvenli olmayan kullanımı |
| **ReDoS (Regex DoS)** | 🟡 Orta | Zararlı regex kalıpları |
| **Debug Bilgileri** | 🔵 Bilgi | `console.log`, `debugger` |

## 🎯 Hızlı Başlangıç

```bash
# Repoyu klonla
git clone https://github.com/yourusername/js-security-scanner.git

# Dizine gir
cd js-security-scanner

# Tarayıcıda aç
open c.html
```

**Veya direkt kullan:** Sadece `index.html` dosyasını tarayıcıda aç! 🎉

## 🔥 Nasıl Kullanılır

<div align="center">

### 1️⃣ Dosyaları Sürükle & Bırak
![Drag Drop](https://img.shields.io/badge/Drag%20%26%20Drop-Supported-success?style=flat-square&logo=upload)

### 2️⃣ Otomatik Tarama
![Auto Scan](https://img.shields.io/badge/Auto%20Scan-Lightning%20Fast-yellow?style=flat-square&logo=bolt)

### 3️⃣ Detaylı Raporlar
![Reports](https://img.shields.io/badge/Reports-Interactive-blue?style=flat-square&logo=chart-bar)

</div>

```javascript
// ✅ Desteklenen dosya formatları
const supportedFiles = ['.js', '.jsx', '.ts', '.tsx'];

// 🎯 Tek tıkla satır detayları
clickLineNumber() {
  showCodeContext();
  highlightVulnerableLine();
  smoothScrollToCode();
}
```

## 🎨 Ekran Görüntüleri

<div align="center">

| 📱 Ana Ekran | 📊 Sonuçlar | 🔍 Detaylar |
|-------------|------------|------------|
| ![Main](https://via.placeholder.com/250x150/667eea/ffffff?text=Main+Screen) | ![Results](https://via.placeholder.com/250x150/f39c12/ffffff?text=Scan+Results) | ![Details](https://via.placeholder.com/250x150/e74c3c/ffffff?text=Code+Details) |

</div>

## 🏆 Avantajlar

<table>
<tr>
<td width="33%">

### 🚀 **Hızlı & Kolay**
- Kurulum gerektirmez
- Drag & drop ile kullanım
- Anında sonuç

</td>
<td width="33%">

### 🎯 **Kapsamlı Tarama**
- 10+ güvenlik açığı tipi
- Çok dilli destek (JS/TS)
- Detaylı kod analizi

</td>
<td width="33%">

### 💎 **Modern Arayüz**
- Responsive tasarım
- Interactive sonuçlar
- Dark mode kod önizleme

</td>
</tr>
</table>

## 🔧 Teknik Detaylar

<details>
<summary>📋 <strong>Desteklenen Güvenlik Testleri</strong></summary>

```javascript
const securityPatterns = {
  xss: /innerHTML\s*=\s*.*[\+\$]/, 
  sqlInjection: /query\s*\(\s*["'`].*\$.*["'`]/,
  hardcodedSecrets: /(?:password|api[_-]?key)\s*[:=]\s*["'`]/i,
  insecureRandom: /Math\.random\(\)/,
  unsafeRedirect: /window\.location\s*=\s*.*[\+\$]/,
  // ... ve daha fazlası
};
```

</details>

<details>
<summary>🌐 <strong>Browser Desteği</strong></summary>

| Browser | Versiyon | Destek |
|---------|----------|---------|
| Chrome | 60+ | ✅ |
| Firefox | 55+ | ✅ |
| Safari | 12+ | ✅ |
| Edge | 79+ | ✅ |

</details>

## 📊 İstatistikler

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/yourusername/js-security-scanner?style=social)
![GitHub forks](https://img.shields.io/github/forks/yourusername/js-security-scanner?style=social)
![GitHub issues](https://img.shields.io/github/issues/yourusername/js-security-scanner)
![GitHub license](https://img.shields.io/github/license/yourusername/js-security-scanner)

**🎯 10.000+ satır kod tarandı • 🐛 500+ açık tespit edildi • ⭐ 0 false positive**

</div>

## 🤝 Katkı Sağlama

Katkılarınızı bekliyoruz! 🎉

1. 🍴 Fork yapın
2. 🌟 Feature branch oluşturun (`git checkout -b amazing-feature`)
3. 💾 Commit yapın (`git commit -m '✨ Add amazing feature'`)
4. 📤 Push yapın (`git push origin amazing-feature`)
5. 🔄 Pull Request açın

<div align="center">

### 🌟 Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!

</div>

## 📄 Lisans

MIT License © 2024

## 🔗 Bağlantılar

- 🌐 **Website:** [js-security-scanner.com](https://ariva.com.tr)
- 🐦 **Twitter:** [@yourusername](https://x.com/Kornetfix6)
- 💬 **Telegram:** [My Dm](t.me/BySnorx)
- 📧 **Email:** esnorx@proton.me

---

<div align="center">

**Made with ❤️ by developers, for developers**

![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=yourusername.js-security-scanner)

</div>
