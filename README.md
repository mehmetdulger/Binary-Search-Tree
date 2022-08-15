# Binary-Search-Tree

Veri Yapıları ve Algoritmalar bölümünde verilen [Binary Search Tree Projesi](https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/binary-search-tree-proje)

**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları**

İlk değer olan 7 root seçilir. 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.

1 değeri 7'den küçüktür, sola tarafa gider, 5'ten de küçüktür o yüzden 5'in sol altına yazılır.

8 değeri 7'den büyüktür, root'un sağ tarafına yazılır.

3 değeri 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır.

6 değeri 7'den küçüktür, 5'ten büyüktür, bu yüzden 5'in sağına yazılır.

0 değeri 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır.

9 değeri 7'den ve 8'den büyüktür, bu yüzden 8'in sağına yazılır.

4 değeri 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, bu yüzden 3'ün sağına yazılır.

2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır.

