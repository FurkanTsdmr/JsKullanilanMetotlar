# JS - Sıkça Kullanılan Metotlar

## String Methods

| Metot                | Açıklama                                                                                  |
|----------------------|-------------------------------------------------------------------------------------------|
| `.concat("birinci", "ikinci")` | String ifadeleri birleştirir.                                                         |
| `.length`            | Karakter sayısını gösterir.                                                               |
| `.toUpperCase()`     | Karakterleri büyük harfe çevirir.                                                         |
| `.toLowerCase()`     | Karakterleri küçük harfe çevirir.                                                         |
| `.indexOf("aranan")` | Aranan ifadenin kaçıncı eleman olduğunu gösterir.                                         |
| `.substring(3,5)`    | Belirtilen aralıktaki ifadeleri getirmek için kullanılır.                                 |
| `.slice(3,5)`        | Belirtilen aralıktaki ifadeleri getirmek için kullanılır.                                 |
| `.replace("eski", "yeni")` | Bir ifadenin değiştirilmesi için kullanılır.                                                |
| `.trim()`            | Boşlukları kaldırır.                                                                      |
| `.split(",")`        | Virgüllerin kullanıldığı yerlerden dizi şeklinde ayırır.                                  |

## Number Methods

| Metot                   | Açıklama                                                                                |
|-------------------------|-----------------------------------------------------------------------------------------|
| `Number("0")`           | İçerisindeki değeri tam sayıya çevirir.                                                 |
| `parseInt("0")`         | İçerisindeki değeri tam sayıya çevirir.                                                 |
| `parseFloat("10.5")`    | İçerisindeki değeri ondalıklı değere çevirir.                                           |
| `isNaN("10")`           | Sayısal bir değer olup olmadığını söyler. Sayısal değer değilse `true` döner.            |
| `.toPrecision(5)`       | Sayıdaki ilk 5 rakamı alır.                                                             |
| `.toFixed(3)`           | Virgülden sonra belirtildiği kadar basamak alır.                                        |

## Math Methods

| Metot                      | Açıklama                                                                            |
|----------------------------|-------------------------------------------------------------------------------------|
| `Math.PI`                  | Pi sayısını getirir.                                                                |
| `Math.round(2.4)`          | Belirtilen sayıyı en yakınına yuvarlar (2).                                         |
| `Math.ceil(2.4)`           | Belirtilen sayıyı yukarıya yuvarlar (3).                                            |
| `Math.floor(2.7)`          | Belirtilen sayıyı aşağıya yuvarlar (2).                                             |
| `Math.sqrt(64)`            | Karekökü almak için kullanılır.                                                     |
| `Math.pow(2, 4)`           | Solda belirtilen rakamın sağdaki kadar üssünü alır.                                 |
| `Math.abs(-100)`           | Mutlak değerini alır.                                                               |
| `Math.min(1, 2, 3, 4, 5, 6)` | Belirtilen sayılar arasındaki en küçük sayıyı getirir.                              |
| `Math.max(1, 2, 3, 4, 5, 6)` | Belirtilen sayılar arasındaki en büyük sayıyı getirir.                              |
| `Math.random()`            | 0-1 arasında rastgele bir sayı üretir.                                              |
| `Math.random() * 10`       | 0 ile 10 arasında rastgele bir sayı üretir.                                         |

## Date & Time Methods

### GET Methods

| Metot           | Açıklama                                                                                       |
|-----------------|------------------------------------------------------------------------------------------------|
| `getDate()`     | Ayın kaçıncı günü olduğunu gösterir.                                                           |
| `getDay()`      | Haftanın kaçıncı günü olduğunu gösterir (0'dan başlar).                                        |
| `getFullYear()` | Yıl bilgisini verir.                                                                           |
| `getHours()`    | Saat bilgisini verir.                                                                          |
| `getMonth()`    | Ay bilgisini verir (0'dan başlar).                                                             |
| `getMinutes()`  | Dakika bilgisini verir.                                                                        |
| `getSeconds()`  | Saniye bilgisini verir.                                                                        |

### SET Methods

| Metot           | Açıklama                                                                                       |
|-----------------|------------------------------------------------------------------------------------------------|
| `setFullYear()` | Yıl değerini değiştirmek için kullanılır.                                                      |
| `setMonth()`    | Ay değerini değiştirmek için kullanılır.                                                       |
| `setDate()`     | Ayın gününü değiştirmek için kullanılır.                                                       |
| `setMinutes()`  | Dakika bilgisini değiştirmek için kullanılır.                                                  |
| `setSeconds()`  | Saniye bilgisini değiştirmek için kullanılır.                                                  |

## Array Methods

| Metot              | Açıklama                                                                                     |
|--------------------|----------------------------------------------------------------------------------------------|
| `.push()`          | En sona eleman eklemek için kullanılır.                                                      |
| `.unshift()`       | En başa eleman eklemek için kullanılır.                                                      |
| `.pop()`           | Dizinin son elemanını silmek için kullanılır.                                                |
| `.shift()`         | Dizinin ilk elemanını silmek için kullanılır.                                                |
| `.indexOf("eleman")` | Arama işlemi yapar ve başladığı index numarasını gösterir.                                  |
| `.reverse()`       | Diziyi ters çevirmek için kullanılır.                                                        |
| `.sort()`          | Sayısal veya alfabetik olarak sıralar (Varsayılan: Artan).                                  |
| `.concat()`        | Dizileri birleştirmek için kullanılır.                                                       |
| `.splice(start, deleteCount, item)` | Dizide belirtilen elemandan sonra, kaç elemanın silineceğini ve eklenecek elemanları belirtir. |
| `.find(condition)` | Parantez içine koşul yazılır (bir fonksiyon olabilir). Koşulu sağlayan ilk elemanı döner.    |
| `.filter(condition)` | Parantez içine koşul yazılır (bir fonksiyon olabilir). Koşulu sağlayan tüm elemanları döner. |
