# Binary-Search-Tree-Projesi

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
    
                            7
                           /  \
                          /    \
                         5      8 
                       /  \     / \
                      /    \   /   \
                     1      6       9
                    / \  
                   /   \
                  0     3 
                       / \
                      2   4
                      
           - Root u 7 olarak aldığımızda ve listeden Binary Search Tree ye sıralı bir şekilde imsertion 
           yaptığımızı var saydığımızda sayılar Binary Search Tree ye şu şekildeeklenir
           - 5 sayısı 7 den küçük olduğu için soluna eklenir
           - 1 sayısı önce root 7 ile karşılaştırılır.7 den  küçük olduğu içim solundaki 5 ile karşılaştırılır.
           Ondan da küçük olduğu için 5 in soluna eklenir
           - 8 sayısı root 7 ile karşılaştırılır.Daha büyük olduğu için 7 nin sağına eklenir.
           - 3 sayısı 7 den ve onun solundaki 5 den küçüktür. Daha sonra 5 in solundaki 1 sayısı ile karşılaştırılır.
           1 den büyük olduğu için 1 in sağına eklenir.
           - 6 sayısı 7 den küçük fakat solundaki 5 den büyüktür ve 5 in sağına yerleştirilir.
           - 0 sayısı root ve onun solundaki 5 ve 1 node larıyla karşılaştırılır. en alt kademedeki 1 den küçük 
           olduğu için 1in soluna yazılır.
           - 9 sayısı root 7  ve onun sağındaki 8 den büyüktür ve 8 in sağına eklenir.
           - 4 sayısı root 7 den ve node 5 den küçüktür fakat node 1 den büyüktür. Node 1 in sağındaki 3 node u ile 
           karşılaştırıldığında ondan da büyük olduğu için 3 ün sağına eklenir
           - 2 sayısı için de 4 sayısı ile aynı karşılaştırmalar yapılır.Fakat 2 3 ten küçüktür ve 3 ün soluna eklenir.
           
