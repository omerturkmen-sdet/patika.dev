#Binary Search Tree

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

      - [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
  Array sorted olmadığı için elemanlara tek tek bakarak gideceğiz. Ortadaki elemanı almayacağız.
  
      - root = 7
      - 5 < 7 olduğu için root elemanının soluna 5'i ekleyeceğiz. 
                        7
                    5    
      
      - 1 < 7  olduğu için sol tarafa yazacağız. 1 < 5 olduğu için 5'in de soluna yazmamız gerekiyor.
                        7
                    5
                1
                
      - 8 > 7  ve root = 7 olduğu için 8'i root elemanın sağına ekliyoruz.
                        7
                    5       8
                1
                       
      - 3 < 7 olduğu için 7'nin soluna, 3 < 5 olduğu için 5'in soluna 3 > 1 olduğu için 1'in sağına ekliyoruz.
                        7
                    5       8
                1
                    3          
                    
      - 6 < 7 olduğu için 7'nin soluna, 6 > 5 olduğu için 5'in sağına ekliyoruz.
                        7
                    5       8
                1      6
                    3
                    
      - 0 < 7 olduğu için 7'nin soluna, 0 < 5 olduğu için 5'in soluna, 0 < 1 olduğu için 1'in soluna ekliyoruz.
                        7
                    5       8
                1      6
             0      3
                             
      - 9 > 7 olduğu için 7'nin sağına, 9 > 8 olduğu için 8'in sağına ekliyoruz.
                        7
                    5       8
                1      6        9
             0      3
                    
                    
      - 4 < 7 olduğu için 7'nin soluna, 4 < 5 olduğu için 5'in soluna, 4 > 1 olduğu için 1'in sağına ve 4 > 3 olduğu için 3'ün sağına ekliyoruz.
                        7
                    5       8
                1      6        9
             0      3
                       4
                             
      - 2 < 7 olduğu için 7'nin soluna, 2 < 5 olduğu için 5'in soluna, 2 > 1 olduğu için 1'in sağına ve 2 < 3 olduğu için 3'ün soluna ekliyoruz.
                        7
                    5       8
                1      6        9
             0      3
                2      4
                
                
  *** Tamamlanmış Hali ***
  
                    7
                  /   \
                 5      8
                / \       \
               1   6       9   
              / \       
             0   3 
               \   \
                2   4
                    
                    
