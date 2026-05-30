# Ayrık Matematik

Ayrık matematiğin temel konularını kapsayan, çalıştırılabilir Python örnekleri, teoremlerin hesaplamalı doğrulaması ve alıştırmalar içeren etkileşimli Jupyter defterleri derlemesi.

## İçindekiler

| # | Defter | Konular |
|---|--------|---------|
| 01 | [Mantık ve İspatlar](notebooks/01_mantik_ve_ispatlar.ipynb) | Önermeler mantığı, doğruluk tabloları, mantıksal denklikler, ispat teknikleri |
| 02 | [Küme Teorisi](notebooks/02_kume_teorisi.ipynb) | Küme işlemleri, kuvvet kümeleri, Kartezyen çarpımlar, küme özdeşlikleri |
| 03 | [Bağıntılar ve Fonksiyonlar](notebooks/03_bagintilar_ve_fonksiyonlar.ipynb) | İkili bağıntılar, denklik bağıntıları, birebir/örten/birebir-örten fonksiyonlar |
| 04 | [Kombinatorik](notebooks/04_kombinatorik.ipynb) | Permütasyonlar, kombinasyonlar, binom teoremi, Pascal üçgeni, güvercin yuvası ilkesi |
| 05 | [Çizge (Graf) Teorisi](notebooks/05_cizge_teorisi.ipynb) | Çizge gösterimi, BFS, DFS, bağlılık |
| 06 | [Sayılar Teorisi](notebooks/06_sayilar_teorisi.ipynb) | EBOB, genişletilmiş Öklid algoritması, modüler aritmetik, Eratosthenes kalburu |
| 07 | [Özyineleme ve Yineleme Bağıntıları](notebooks/07_ozyineleme_ve_bagintilar.ipynb) | Özyinelemeli tanımlar, belleğe alma, yineleme bağıntıları, tümevarım |
| 08 | [Boole Cebiri](notebooks/08_boole_cebiri.ipynb) | Boole fonksiyonları, mantık kapıları, normal formlar, fonksiyonel tamlık |

## Başlangıç

```bash
git clone https://github.com/HAYDARKILIC/discrete_mathematics.git
cd discrete_mathematics
pip install -r requirements.txt
jupyter notebook
```

Ardından `notebooks/` klasöründeki herhangi bir defteri açıp hücreleri çalıştırın.

## Gereksinimler

- Python 3.8+
- Jupyter
- Örneklerin çoğu yalnızca standart kütüphaneyi kullanır (ağır bağımlılık yok).

Ayrıntılar için [`requirements.txt`](requirements.txt) dosyasına bakın.

## Nasıl Kullanılır

Her defter kendi içinde bütündür ve aynı yapıyı izler:

1. Matematiksel notasyonla **kavram açıklaması** (Markdown).
2. Kavramı uygulayan ve gösteren **çalıştırılabilir kod**.
3. Temel teorem ve özdeşliklerin **hesaplamalı doğrulaması**.
4. Sonda daha fazla pratik için **alıştırmalar**.

## Lisans

Bu proje MIT Lisansı ile lisanslanmıştır — ayrıntılar için [LICENSE](LICENSE) dosyasına bakın.

## Yazar

**HAYDARKILIC** — [GitHub](https://github.com/HAYDARKILIC)
