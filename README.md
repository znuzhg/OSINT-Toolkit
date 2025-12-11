```markdown
# 🛰️ OSINT Toolkit  
*Kapsamlı Açık Kaynak İstihbarat (OSINT) Araç Koleksiyonu*

<p align="center">
  <img src="https://img.shields.io/badge/OSINT-Toolkit-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Active-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

Bu depo, siber güvenlik öğrencileri, analistler ve red team/pentest meraklıları için hazırlanmış **modüler bir OSINT araç koleksiyonudur**.  
Amaç, keşif, sosyal medya analizi, metadata inceleme, veri sızıntısı araştırmaları ve tehdit istihbaratı süreçlerinde kullanılan en popüler araçları **tek bir merkezi toolkit altında toplamak** ve düzenli bir yapı sunmaktır.

---

# 📂 Klasör Yapısı

```text
OSINT-Toolkit/
│
├── reconnaissance/        # DNS, domain, subdomain keşfi & tarama
├── social-media/          # Profil, kullanıcı adı & sosyal medya OSINT
├── email-phone/           # Telefon ve e-posta tabanlı araştırma
├── data-leaks/            # Sızıntı dosyaları & breach analizi
├── metadata/              # EXIF & doküman metadata inceleme araçları
├── github-osint/          # GitHub dorking, kod arama & OSINT araçları
├── frameworks/            # Büyük OSINT platform & framework setleri
├── GHunt/                 # Google Account OSINT
├── informacam-guide/      # Kamera/çevrim içi metadata rehберleri
└── README.md
```

---

# 🔍 Araç Kategorileri ve Özellikleri

## 1️⃣ Reconnaissance (Keşif)
| Araç | Açıklama |
|------|----------|
| **Amass** | Pasif/aktif alt domain keşfi – enterprise seviyede |
| **Subfinder** | Çok hızlı alt domain toplama |
| **Nuclei** | Template tabanlı zafiyet & keşif taramaları |
| **theHarvester** | E-posta, domain, subdomain, kaynak toplama |

---

## 2️⃣ Sosyal Medya OSINT
| Araç | Açıklama |
|------|----------|
| **Sherlock** | Kullanıcı adı tespiti – yüzlerce platform |
| **Maigret** | 500+ platformda kullanıcı adı kontrolü |
| **Twint** | API kullanmadan Twitter(X) OSINT toplama |

---

## 3️⃣ Telefon & Email OSINT
| Araç | Açıklama |
|------|----------|
| **Holehe** | Bir e-postanın kayıtlı olduğu siteleri bulur |
| **PhoneInfoga** | Telefon numarası OSINT, carrier & region bilgisi |
| **PwnedOrNot** | Veri sızıntılarında email kontrolleri |

---

## 4️⃣ Veri Sızıntısı & Breach Analizi
| Araç | Açıklama |
|------|----------|
| **Breach-Parse** | Dump & wordlist ayrıştırıcı |
| **LeakScraper** | Açık veri sızıntılarından bilgi çıkarmak için |

---

## 5️⃣ Metadata Analizi
| Araç | Açıklama |
|------|----------|
| **ExifTool** | EXIF metadata çıkarıcı – foto & doküman |
| **FOCA** | PDF/Doc metadata çıkartma & network map üretimi |
| **CameraV / InformaCam** | Kamera doğrulama ve metadata manipülasyon analizi |

---

## 6️⃣ GitHub OSINT
| Araç | Açıklama |
|------|----------|
| **GitDorker** | GitHub üzerinde gelişmiş dorking |
| **dorksearch** | Arama tabanlı OSINT |

---

## 7️⃣ Framework & Analiz Platformları
| Framework | Açıklama |
|----------|----------|
| **OSINT-Framework** | OSINT kaynak haritası |
| **SpiderFoot** | 500+ modüllü otomasyon framework |
| **Recon-ng** | Modüler keşif çerçevesi |
| **Yeti** | Threat intelligence platform |
| **OpenCTI** | Açık kaynak tehdit istihbaratı sistemi |

---

# ⚙️ Kurulum

Her aracın klasöründe kendi **README**, **install**, veya **requirements** dosyası vardır.  
Temel kurulum örnekleri:

## Python Araçları
```bash
pip install -r requirements.txt
```

## Go Tabanlı Araçlar
```bash
go install ./...
```

## Docker Üzerinden Kullanım
```bash
docker build -t toolname .
docker run -it toolname
```

---

# 🧭 Örnek OSINT Workflow

1. **Reconnaissance** → Domain & subdomain toplama  
2. **Metadata Analysis** → Fotoğraf/dosya EXIF çıkarma  
3. **Identity/Footprint OSINT** → Mail/telefon/sosyal medya araştırmaları  
4. **GitHub OSINT** → Kod sızıntısı arama  
5. **Leak Analysis** → Sızmış dump dosyalarını analiz etme  
6. **Threat Intelligence** → Çıkan bulguları OSINT framework'lere aktarma  

---

# ⚖️ Legal Uyarı

Bu araçlar yalnızca:

- ✔ Eğitim amaçlı  
- ✔ Kendi sistemlerinizde  
- ✔ Yazılı izin alınmış hedeflerde  

kullanılmalıdır.

**İzinsiz tarama, veri toplama veya saldırı denemesi yasa dışıdır ve siz sorumlu olursunuz.**

---

# 🤝 Katkıda Bulunmak

- Yeni araç önerileri  
- Performans geliştirmeleri  
- Yeni OSINT workflow’ları  

Pull-request'ler memnuniyetle karşılanır! 🚀

---

# ⭐ Destek

Eğer bu repo hoşunuza gittiyse bir ⭐ bırakmayı unutmayın — OSINT topluluğuna katkı sağlamış olursunuz.

```
