# Proje 1
## Insertion Sort
**[22,27,16,2,18,6]** 

1 - Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

&nbsp;&nbsp;&nbsp;[22,27,16,**2**,18,6]
1-[2,27,16,22,18,**6**]
2-[2,6,**16**,22,18,27] Halihazırda olması gereken yerdedir.
3-[2,6,16,22,**18**,27]
4-[2,6,16,18,**22**,27] Halihazırda olması gereken yerdedir.
5-[2,6,16,18,22,**27**]

2 - Big-O gösterimini yazınız.

n + (n-1) + (n-2) + ... + 1 kez kontrol yapılacağı için 
n*(n+1)/2

***Cevap*** ***O(n^2)***

3 - Time Complexity

-worst case: Elemanlar istenilenin tam zıddı sıralamışsa; O(n^2)
-average case; O(n^2)
-best case: Halihazırda istenilen sıralama varsa; O(n)

4 - Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

Average case kapsamına girer.

---

**[7,3,5,8,2,9,4,15,6]** dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

&nbsp;&nbsp;&nbsp;[7,3,5,8,**2**,9,4,15,6]
1-[2,**3**,5,8,7,9,4,15,6] Halihazırda olması gereken yerdedir.
2-[2,3,5,8,7,9,**4**,15,6]
3-[2,3,4,8,7,9,**5**,15,6]
4-[2,3,4,5,7,9,8,15,**6**]
5-[2,3,4,5,6,9,8,15,**7**]
6-[2,3,4,5,6,7,**8**,15,9] Halihazırda olması gereken yerdedir.
7-[2,3,4,5,6,7,8,15,**9**]
8-[2,3,4,5,6,7*8,9,15]