# Object Tracking

## Getting Started

Install library yang dibutuhkan

```
pip install numpy
pip install scipy
pip install imutils
```

## The Centroid tracking algorithm

Algoritma ini menghitung centroid dari objek yang terdeteksi dan membandingkan centroid yang baru dengan centroid yang lama. Jika centroid yang baru dan centroid yang lama memiliki jarak yang cukup dekat, maka objek tersebut dianggap sebagai objek yang sama. Jika centroid yang baru dan centroid yang lama memiliki jarak yang cukup jauh, maka objek tersebut dianggap sebagai objek yang baru.

## How the centroid tracking algorithm works

1. Menerima kooridinat bounding box dari objek yang terdeteksi.
   Algoritma centroid berasumsi bawah user mengirim satu set bounding box memiliki x dan y pada setiap frame
2.
