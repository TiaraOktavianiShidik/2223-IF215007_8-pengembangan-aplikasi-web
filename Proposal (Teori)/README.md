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

### Session
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
![Untitled35_20220912002334](https://user-images.githubusercontent.com/76018503/189540850-562aa22b-c120-4ebf-b09e-38f60b7334c4.png)
![Untitled36_20220912002314](https://user-images.githubusercontent.com/76018503/189540867-d12c982c-d3c3-406c-8dff-50da1b80f50f.png)
