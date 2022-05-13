# veri-yapilari-ve-algoritmalar-patika-dev-data-analyst-path

Proje 1:

array = [22,27,16,2,18,6]

# 1 - Insertion Sort Aşamaları:

1 - En küçük elemanı bulma ve en baştaki ile yer değiştirme 
 -> [2,27,16,22,18,6]
 Artık '2' elemanını kilitledik. Ona dokunmuyoruz. 

2 - 2 hariç en küçük elemanı bulma ve yer değiştirme.
 -> [2,6,16,22,18,27]

3 - 2,6 ve 16 hariç en küçük elemanı bulma ve yer değiştirme. 
 -> [2,6,16,22,18,27]

4 - Son adım.
 -> [2,6,16,18,22,27]
 Ve bu şekilde insertion sort algoritmasını tamamlamış oluyoruz.

# 2 - Big O Gösterimi
Her seferinde tüm array gezilip, en küçüğü arandığı için; <p>O(N^2)</p>

# 3 - Time Complexity
<ul>
 <li>Average Case: Aradığımız sayının ortada olması.</li>
 <li>Worst Case: Aradığımız sayının sonda olması.</li>
 <li>Best Case: Aradığımız sayının dizinin en başında olması.</li>
 
 </ul>

# 4 - Dizi sıralandıktan sonra, 18; Worst Case kapsamına girer.

<h2> 5 - [7,3,5,8,2,9,4,15,6] dizisinin, insertion sort'a göre ilk 4 adımı: </h2>
 <ol>
 <li>[2,3,5,8,7,9,4,15,6]</li>
 <li>[2,3,4,8,7,9,5,15,6]</li>
 <li>[2,3,4,5,7,9,8,15,6]</li>
 <li>[2,3,4,5,6,9,8,15,7]</li>
 </ol>
 
 <p>.. Şeklinde devam etmektedir.</p>



