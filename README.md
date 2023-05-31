# MergeSortProject
Patika Veri Yapıları ve Algoritmalar - Merge Sort Projesi

## Soru

[16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.


## Cevap

[16,21,11,8,12,22] -> Merge Sort

### Yukarıda verilen dizinin sort türüne göre aşamaları:

                                   
   |16, 21, 11, 8, 12, 22|         
       /             \             
|16, 21, 11|     |8, 12, 22|       
     /    \            /   \       
|16, 21|  |11|     |8,12|  |22|    
    /  |   \          /  |   \     
|16| |21| |11|     |8| |12| |22|   
  |     \  /        |    \   /     
|16|  |11, 21|     |8|  |12,22|    
  \      /          |    /         
|11, 16, 21|     |8,12,22|         
     \              /             
   |8, 11, 12, 16, 21, 22|         


### Big-O Gösterimi:

O(n.logn) şeklinde olur.
