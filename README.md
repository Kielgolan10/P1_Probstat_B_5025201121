### Praktikum 1 [ Probabilitas & Statistika ]





## Soal
1. Seorang penyurvei secara acak memilih orang-orang di jalan sampai dia bertemu dengan
   seseorang yang menghadiri acara vaksinasi sebelumnya.
   
    - Berapa peluang penyurvei bertemu x = 3 orang yang tidak menghadiri acara vaksinasi
      sebelum keberhasilan pertama ketika p = 0,20 dari populasi menghadiri acara vaksinasi ?
      (distribusi Geometrik)
       
       ```yml
        p = 0.2
        n = 3
        dgeom(x = n, prob = p)
       ```
       #### result:
       ```yml
       > p = 0.2
       > n = 3
       > dgeom(x = n, prob = p)
       0.1024
       ```
    - mean Distribusi Geometrik dengan 10000 data random , prob = 0,20 dimana distribusi
      geometrik acak tersebut X = 3 ( distribusi geometrik acak () == 3 )
      
      ```yml
      mean(rgeom(n = 10000, prob = p) == 3)
      ```
      
      #### result:
      ```yml
      0.1002
      ```
    - Bandingkan Hasil poin a dan b , apa kesimpulan yang bisa didapatkan?:
      Hasil banding menunjukkan bahwa ketika peluang n dari data random maka akan menghasilkan nilai yang berbeda
       

    
    
    
    
    
    
    



















| Nama                      | NRP           |
|---------------------------|---------------|
|Gloriyano C. Daniel Pepuho |5025201121     |
