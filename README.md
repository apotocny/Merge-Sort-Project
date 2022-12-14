Merge Sort Projesi

Proje 2   [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

-------------------------------------------------------------

Cevap 1 : 


Merge Sort		:				[16,21,11,8,12,22]

					  [16,21,11]		    [8,12,22] 	-----> Öncelikle dizideki sayıları üçerli iki gruba ayırıyoruz.


					[16]	[21,11]		[8,12]	[22]	-----> Üçerli iki gruptaki sayıları kendi içinde de biri tek 

													 diğeri ikili olacak şekilde 2 ayrı gruba ayırıyoruz.

					[16] [21] [11]		  [8] [12] [22]	-----> Kendi içinde ikili gruba ayırdığımız sayıları kendi 

													 içinde tek kalana kadar ayırıyoruz.

					[16]	[11,21]		[8,12]	[22]	-----> Tekli halde olan sayıları yeniden 2 ayrı grupta toplarken

													 ikili olan sayılar küçükten büyüğe doğru sıralanıyor.

					[11,16,21]			[8,12,22]		-----> İkili olan sayıları yeniden birleştirirken kendi aralarında 

													 küçükten büyüğe doğru sıralanır.

							[8,11,12,16,21,22]		-----> Son olarak iki ayrı gruptaki sayıları bir araya getirirken 

													 küçükten büyüğe doğru sıralayarak tek dizi haline getiriyoruz.



-------------------------------------------------------------

Cevap 2 			:	Big-O gösterimi aşağıdadır.

					Big-O notation O(nlogn)
