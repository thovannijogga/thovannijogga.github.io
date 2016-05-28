---
layout: post
title: "Universitas Islam Negeri Sultan Syarif Kasim Riau (UIN SUSKA)"
author: billy_rick
modified:
excerpt: "Universitas Islam Negeri Sultan Syarif Kasim (UIN Suska) Riau dalam bahasa Arab adalah  جامعة السلطان شريف قاسم الإسلامية اﻟﺤﻜﻮمية رياو dan dalam bahasa Inggris adalah State Islamic University of Sultan Syarif Kasim Riau merupakan hasil pengembangan/ peningkatan status pendidikan dari Institut Agama Islam Negeri (IAIN) Sulthan Syarif Qasim Pekanbaru yang secara resmi dikukuhkan berdasarkan Peraturan Presiden RI Nomor 2 Tahun 2005 tanggal 4 Januari 2005 tentang Perubahan IAIN Sulthan Syarif Qasim Pekanbaru menjadi UIN Sultan Syarif Kasim Riau dan diresmikan pada 9 Februari 2005 oleh Presiden RI, Bapak Dr. H. Susilo Bambang Yudhoyono sebagai tindak lanjut perubahan status ini, Menteri Agama RI menetapkan Organisasi dan Tata kerja UIN Suska Riau berdasarkan Peraturan Menteri Agama RI Nomor 8 Tahun 2005 tanggal 4 April 2005.

Institut Agama Islam Negeri Sulthan Syarif Qasim (IAIN Susqa) Pekanbaru sebagai cikal bakal UIN Suska Riau, didirikan pada tanggal 19 September 1970 berdasarkan Surat Keputusan Menteri Agama Republik Indonesia No. 194 Tahun 1970. Institut ini diresmikan berdirinya oleh Menteri Agama Republik Indonesia K.H. Ahmad Dahlan pada tanggal 19 September 1970 berupa penandatanganan piagam dan pelantikan Rektor yang pertama, Prof. H. Ilyas Muhammad Ali.."
tags: []
---

For those of you who may have content written by multiple authors on your site you can now assign different authors to each post if desired.

Previously the theme used a global author for the entire site and those attributes would be used in all bylines, social networking links, Twitter Card attribution, and Google Authorship. These `owner` variables were defined in `config.yml`

Start by modifying or creating a new `authors.yml` file in the `_data` folder and add your authors using the following format.

{% highlight yaml %}
# Authors

billy_rick:
  name: Billy Rick
  web: http://thewhip.com
  email: billy@rick.com
  bio: "What do you want, jewels? I am a very extravagant man."
  avatar: bio-photo-2.jpg
  twitter: extravagantman
  google:
    plus: BillyRick

cornelius_fiddlebone:
  name: Cornelius Fiddlebone
  email: cornelius@thewhip.com
  bio: "I ordered what?"
  avatar: bio-photo.jpg
  twitter: rhymeswithsackit
  google:
    plus: CorneliusFiddlebone
{% endhighlight %}

To assign Billy Rick as an author for our post. You'd add the following YAML front matter to a post:

{% highlight yaml %}
author: billy_rick
{% endhighlight %}
