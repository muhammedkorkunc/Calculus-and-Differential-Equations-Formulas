# 📐 Calculus & Differential Equations Comprehensive Formula Archive

### Lisans Düzeyi Kalkülüs-1, Kalkülüs-2 ve Diferansiyel Denklemler Referans Kütüphanesi

Bu depo; Bilgisayar Mühendisliği lisans eğitimi boyunca hazırlanan **Kalkülüs I (Tek Değişkenli Analiz)**, **Kalkülüs II (Çok Değişkenli Analiz, Seriler ve Geometrik İntegral Uygulamaları)** ve **Diferansiyel Denklemler** derslerine ait formülasyonları, çözüm algoritmalarını ve analitik ispat yöntemlerini içerir.

---

## 📑 Kapsanan Matematiksel Modüller ve İçerikler

| Doküman | Başlık                      | Kapsanan Temel Konular ve Analitik Yöntemler                                                                                                                                                                                                                                                                                                                                                          |
| :------ | :-------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **01**  | **Diferansiyel Formülleri** | Ayrılabilir denklemler, homojen denklem çözümleri, tam diferansiyeller, integral çarpanı, Bernoulli ve Riccati denklemleri, mertebe indirgeme (reduction of order), Cauchy-Euler denklemleri, Laplace ve ters Laplace dönüşümleri, basamak (Heaviside) fonksiyonları, matris özdeğer-özvektör yöntemi, kuvvet serileri (power series) ile adi nokta (ordinary point) çözümleri.                       |
| **02**  | **Diziler ve Seriler**      | Dizilerde yakınsaklık ve ıraksaklık limitleri, n. terim testi, geometrik seri toplam formülleri, p-serisi testi, integral testi, doğrudan ve limit karşılaştırma testleri, oran testi (ratio test), kök testi (root test), alterne seriler ve mutlak/koşullu yakınsaklık, kuvvet serilerinde yakınsaklık yarıçapı/aralığı, Taylor ve Maclaurin seri açılımları.                                       |
| **03**  | **Türev ve İntegral**       | Temel ve ters trigonometrik türev kuralları, parametrik fonksiyonların 1. ve 2. türevleri, L'Hospital kuralı, logaritmik türev, kısmi integrasyon (tabular method), trigonometrik dönüşümler, genelleştirilmiş integraller (improper integrals), dönel cisimlerin hacim hesapları (Disk, Washer ve Silindirik Kabuk/Shell yöntemleri), yay uzunluğu (arc length) ve parametrik yüzey alanı hesapları. |

---

## 📐 Öne Çıkan Formülasyonlar ve Yöntemler

### 1. Dönel Cisimlerde İntegral ile Hacim Hesabı

- **Disk / Washer Yöntemi (x-ekseni etrafında):**
  $$V = \pi \int_{a}^{b} \left( [f(x)]^2 - [g(x)]^2 \right) dx$$

- **Silindirik Kabuk / Shell Yöntemi (y-ekseni etrafında):**
  $$V = 2\pi \int_{a}^{b} r \cdot h \, dx = 2\pi \int_{a}^{b} x \cdot f(x) \, dx$$

---

### 2. Diferansiyel Denklemlerde Laplace Dönüşümü

Zaman domeninden frekans domenine geçiş:

$$\mathcal{L}\{f(t)\} = F(s) = \int_{0}^{\infty} f(t) e^{-st} \, dt$$

Türevlerin Laplace dönüşümleri ve Heaviside öteleme teoremi:

- $\mathcal{L}\{y'\} = s Y(s) - y(0)$
- $\mathcal{L}\{y''\} = s^2 Y(s) - s y(0) - y'(0)$
- $\mathcal{L}\{u_a(t) f(t - a)\} = e^{-as} F(s)$

---

### 3. Serilerde Oran ve Kök Testi

- **Oran Testi (Ratio Test):**
  $$L = \lim_{n \to \infty} \left\vert{} \frac{a_{n+1}}{a_n} \right\vert{} \quad (L < 1 \implies \text{Yakınsak}, \quad L > 1 \implies \text{Iraksak})$$

- **Taylor Seri Açılımı ($x = x_0$ civarında):**
  $$f(x) = \sum_{n=0}^{\infty} \frac{f^{(n)}(x_0)}{n!} (x - x_0)^n$$

---

## 🔒 Copyright & License / Telif Hakkı Bildirimi

Bu arşiv ve beraberindeki el yazması/sayısal formül kılavuzları **Proprietary (Tescilli / Tüm Hakları Saklıdır)** lisansına tabidir.

```text
Copyright (c) 2026 Muhammed Emin Korkunç. All Rights Reserved.

Bu çalışmadaki tüm matematiksel özetler, grafiksel metotlar, çıkarımlar
ve formül derlemeleri Muhammed Emin Korkunç'a aittir. Yazarın açık yazılı
izni olmaksızın kısmen veya tamamen kopyalanması, paylaşılması veya
akademik/ticari amaçla izinsiz kullanımı kesinlikle yasaktır.
```
