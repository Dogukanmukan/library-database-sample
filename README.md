# Kütüphane Veritabanı Projesi

Bu proje, bir kütüphane yönetim sistemi için örnek bir veritabanı yapısı sunmaktadır. Amaç, kitaplar, yazarlar, üyeler ve ödünç alma işlemleri gibi temel kütüphane bileşenlerini kapsayan bir veritabanı modeli oluşturmaktır.

## İçindekiler
- [Özellikler](#özellikler)
- [Kullanılan Teknolojiler](#kullanılan-teknolojiler)
- [Kurulum](#kurulum)
- [Veritabanı Yapısı](#veritabanı-yapısı)
- [Kullanım](#kullanım)
- [Katkı](#katkı)
- [Lisans](#lisans)

## Özellikler
- **Kitap Yönetimi**: Kitapların eklenmesi, güncellenmesi ve silinmesi.
- **Yazar Yönetimi**: Yazar bilgilerini ekleme ve güncelleme.
- **Üye Yönetimi**: Kütüphane üyelerinin kayıt ve takibi.
- **Ödünç Alma İşlemleri**: Kitap ödünç alma ve iade süreçlerinin yönetimi.

## Kullanılan Teknolojiler
- **Veritabanı Yönetim Sistemi**: MySQL
- **Programlama Dili**: SQL
- **Geliştirme Ortamı**: MySQL Workbench veya benzeri bir SQL istemcisi

## Kurulum
1. **Depoyu Klonlayın**:
    ```bash
    git clone https://github.com/Dogukanmukan/library-database-sample.git
    ```
2. **Veritabanını Oluşturun**:
    - MySQL sunucunuzda yeni bir veritabanı oluşturun:
      ```sql
      CREATE DATABASE kutuphanedb;
      ```
3. **Tabloları ve Verileri İçe Aktarın**:
    - `kutuphanedb` dizinindeki SQL dosyalarını sırasıyla çalıştırarak tabloları oluşturun ve örnek verileri ekleyin.

## Veritabanı Yapısı
Veritabanı aşağıdaki temel tabloları içerir:

- **Kitaplar**: Kitap bilgileri (ISBN, başlık, yazar, kategori, sayfa sayısı, puan).
- **Yazarlar**: Yazarın adı ve soyadı.
- **Üyeler**: Üye bilgileri (ad, soyad, cinsiyet, doğum tarihi, sınıf).
- **İşlemler**: Ödünç alma ve iade işlemleri (üye no, kitap no, alış tarihi, iade tarihi).

## Kullanım
- Veritabanını oluşturduktan sonra, SQL sorguları kullanarak kitap, yazar ve üye bilgilerini ekleyebilir, güncelleyebilir veya silebilirsiniz.
- Ödünç alma ve iade işlemlerini yönetmek için ilgili tabloları kullanabilirsiniz.

## Katkı
1. Projeyi forkladıktan sonra geliştirmelerinizi kendi branşınızda yapabilirsiniz.
2. Değişikliklerinizi commit edin ve GitHub’a push yapın.
3. Bir `pull request` oluşturarak önerilerinizi paylaşabilirsiniz.

## Lisans
Bu proje MIT Lisansı ile lisanslanmıştır. Ayrıntılar için `LICENSE` dosyasına bakabilirsiniz.
