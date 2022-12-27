# Proposal : Time Tracker

## Permasalahan
- Mahasiswa merasa kesulitan dalam mengatur waktu belajar di tengah banyaknya distraksi dan jadwal kegiatan yang belum tersusun dengan baik.

## Rancangan Solusi
- Aplikasi yang dapat membantu untuk memantau berapa banyak waktu yang dapat dihabiskan untuk belajar, beristirahat, bermain, dll. sehingga dapat diketahui tingkat produktivitas kita setiap harinya.

## Use Case
- User bisa membuat *new session* secara manual dengan menentukan *session start* dan *session end*-nya.
- User bisa membuat kategori-kategori untuk mengkategorikan setiap *session*.
- User bisa mengikuti fitur challenge untuk menunjang produktivitas.

## Struktur Data

### User
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 222
username | string | okta
password | string | via123

### Session
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 12
title | string | belajar web
date | date | 11-09-2022
session_start | time | 07:00:00
session_end | time | 08:00:00
category | string | study

### Category
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 25
nama_category | string | study

## UX Wireframe
![time-tracker](https://user-images.githubusercontent.com/76018503/197400029-501e61c7-29d4-414b-b1d7-ae5723a5c499.png)
