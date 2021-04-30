package com.example.kotlin_btk_001

import androidx.appcompat.app.AppCompatActivity
import android.os.Bundle

class MainActivity : AppCompatActivity() {
    override fun onCreate(savedInstanceState: Bundle?) {
        super.onCreate(savedInstanceState)
        setContentView(R.layout.activity_main)
        //********Değişkenler*********
        println("********Değişkenler*********") // yazacak
        println("******** var *********")  // yazacak
        println("Merhaba Dünyalı") // yazacak
        println(5*10)   // 5 * 10 = 50 yazacak

        var a = 10

        var b = 4

        var yas = a * b  // a = 10 b = 4

        println(yas)  // yas = 10*4 = 40 yazacak

        yas = 80 // yas'ın yeni değeri 80 oldu

        println(yas)  // yas'ın yeni değeri olan 80 yazacak

        yas = 60  // yas'în yeni değeri 60 oldu

        println(yas/5*8)

        // 60 / 5 * 8  işlem sırasına dikkat!! 60 / 5 = 12 * 8 = 96 yazacak

        // değişkenler var ile tanımlanır.

        // bir kere tanımlandıktan sonra değiştirilebilirler.

        println("********Sabitler*********")  // yazacak

        println("******** val *********")  // yazacak

        val c=15    // sabitimiz olan  c = 15 oldu  // bidaha değiştiremeyeceğiz

        println(c)  // c = 15  yazacak

        val d=20

        val e=5

        println(d+e) //d = 20   e = 5  d+e = 25  yazacak

        yas=b*e   // b = 4   e = 5

        println(yas)  // 20  yazacak

        // iki ve daha fazla kelimeli yazımların iki çeşit yazım tarzı var

        // 1        camelCase  yasSonucu

        //          * Kotlin'de camelCase kullanılıyor.

        // 2        snake_case  yas_sonucu

        val yasSonucu = yas  * e

        println(yasSonucu) // yas = 20 , e = 5  ise yasSonucu = 20*5 = 100 yazacak


    }
}
