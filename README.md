# Binary Search Tree Projesi
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Quick Sort aşamalarını yazınız.

||[7|5|1|8|3|6|0|9|4|2]|Binary Search Tree|
|-|-|-|-|-|-|-|-|-|-|-|-|
|||||||7|||||Seviye 0 Root
|||||| / || \ ||||
|||||5||||8|||Seviye 1
|||| / || \ |||| \ ||
|||1||||6||||9|Seviye 2
|| / || \ ||||||||
|0||||3|||||||Seviye 3
|||| / || \ ||||||
|||2||||4|||||Seviye 4

>Aşamalar
>* İlk değer olan 7 root seçilir. 5 değeri root değerinden küçük olduğu için sol tarafa yazılır.
>* 1 değeri 7'den küçüktür, sola tarafa gider, 5'ten de küçüktür o yüzden 5'in sol altına yazılır.
>* 8 değeri 7'den büyüktür, root'un sağ tarafına yazılır.
>* 3 değeri 7'den küçüktür, 5'ten küçüktür ama 1'den büyüktür, bu yüzden 1'in sağ tarafına yazılır.
>* 6 değeri 7'den küçüktür, 5'ten büyüktür, bu yüzden 5'in sağına yazılır.
>* 0 değeri 7'den, 5'ten ve 1'den küçüktür, bu yüzden 0'ın soluna yazılır.
>* 9 değeri 7'den ve 8'den büyüktür, bu yüzden 8'in sağına yazılır.
>* 4 değeri 7'den ve 5'den küçüktür, 1'den ve 3'ten büyüktür, bu yüzden 3'ün sağına yazılır.
>* 2 değeri 7'den ve 5'den küçüktür, 1'den büyük ama 3'den küçüktür, bu yüzden 3'ün soluna yazılır.

Big-O gösterimini yazınız.

>Avarage Case: O(logn)

>Düzgünce yarıya bölemediği durumlarda ağaç dengesiz ise Worst Case: O(n)

# Link
[www.patika.dev](https://www.patika.dev/)