# Veri Yapıları ve Algoritmalar

## **Proje 1**

**[22,27,16,2,18,6]** -> Insertion Sort

	1. Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
		
		- [22,16,27,2,18,6]
		- [16,22,27,2,18,6]
		- [16,22,2,27,18,6]
		- [16,2,22,27,18,6]
		- [2,16,22,27,18,6]
		- [2,16,22,18,27,6]
		- [2,16,18,22,27,6]
		- [2,16,18,22,6,27]
		- [2,16,18,6,22,27]
		- [2,16,6,18,22,27]
		- [2,6,16,18,22,27]
		
	2. Big-O gösterimini yazınız.
	
		- O(n^2)
		
	3. Time Complexity:
		
		- Best case: n
		- Worst case: n^2
		- Average case: n^2
		
	4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
	
		- Average case.
	
**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

		- [3,7,5,8,2,9,4,15,6]
		- [3,5,7,8,2,9,4,15,6]
		- [3,5,7,2,8,9,4,15,6]
		- [3,5,2,7,8,9,4,15,6]

---

## **Proje 2**

**[16,21,11,8,12,22]** -> Merge Sort
	
	1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
		
		-    [16,21,11]	    ,	  [8,12,22]
		         \/		      \/
		-  [16,21] , [11]	[8,12] , [22]
		      \/		  \/
		- [16],[21] [11]	[8],[12] [22]
		     \ /		  \  /
		-  [16,21]  [11]	  [8,12] [22]
			 \  /		       \ /
		-     [11,16,21]	    [8,12,22]
			   \			/
		-	     [8,11,12,16,21,22]
		
	2. Big-O gösterimini yazınız.
		
		- O(nlogn)
---

## **Proje 3**

**[7,5,1,8,3,6,0,9,4,2]** dizisinin Binary-Search-Tree aşamalarını yazınız.
(Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb. )

		- Kök: 7 / sağında x > 7 / solunda x < 7
		- 	
					7
				       / \
				      5   8
				     / \   \ 
				    1	6   9
				   / \
				  0   3
				     / \
				    2   4
		      
---

## **Links**

[patika.dev](www.patika.dev)
