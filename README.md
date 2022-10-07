# Insertion-Sort-Odevi

#  [22,27,16,2,18,6] --> Insertion Sort
# 1) Verilen dizinin sort türüne göre aşamalarını yazınız. 

# --> [2, 27, 16, 22, 18, 6]
# --> [2, 6, 16, 22, 18, 27]
# --> [2, 6, 16, 18, 22, 27]
# --> [2, 6, 16, 18, 22, 27]

# 2) Big-o Gösterimini yazınız.

# n + (n-1) + (n-2) + .... + 1 = (n*(n+1))/2 = (n^2 + n)/2 = (n^2/2) + (n/2)
# Big-o notation = O(n^2)


3) #Best case : Aradığımız sayının en başta olması.
   #Average case : Aradığımız sayının ortada olması.
   #Worst case : Aradığımız sayının sonda olması
   
4) Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? 

# [2, 6, 16, 18, 22, 27] serisinde dizinin ortasında 16 ve 18 değerleri bulunuyor. Bu sebeple 18 sayısı average case kapsamına giremektedir.

5) [7,3,5,8,2,9,4,15,6] dizisinin insertion sort'a göre ilk 4 adımını yazınız.

# --> [2,3,5,8,7,9,4,15,6]
# --> [2,3,4,8,7,9,5,15,6]
# --> [2,3,4,5,7,9,8,15,6]
# --> [2,3,4,5,6,9,8,15,7]
