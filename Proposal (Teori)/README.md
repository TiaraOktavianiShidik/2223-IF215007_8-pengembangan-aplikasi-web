# Proposal : Time Tracker and Schedule

## Permasalahan
- Mahasiswa merasa kesulitan dalam mengatur waktu belajar di tengah banyaknya distraksi dan jadwal kegiatan yang belum tersusun dengan baik.

## Rancangan Solusi
- Aplikasi yang dapat membantu untuk memantau berapa banyak waktu yang dapat dihabiskan untuk belajar, beristirahat, bermain, dll. dan membantu menyusun jadwal kegiatan dengan baik dan sistematis.

## Use Case
- User bisa melakukan registrasi dan login.
- User bisa membuat *new session* baik secara otomatis dengan menggunakan timer ataupun secara manual dengan menentukan *session start* dan *session end*-nya.
- User bisa membuat kategori-kategori *tags* sebagai penanda *session*
- User bisa melihat statistik produktivitas per hari dalam seminggu ataupun sebulan.
- User bisa mengelola jadwal.

## Struktur Data

### User
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 222
username | string | okta
password | string | via123

### Session Timer
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 12
title | string | jogging
tags | string | sport

### Session Manual
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 12
title | string | jogging
date | date | 11-09-2022
session_start | time | 07:00:00
session_end | time | 08:00:00
tags | string | sport

### Tag
Atribut|Tipe Data|Contoh
---|---|---
ID | integer | 25
name_tag | string | sport
color | string | red

## UX Wireframe

