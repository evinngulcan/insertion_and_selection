
  <div><h2>Insertion Sort Aşamaları:</h2>
    <p>Verilen dizi: [22,27,16,2,18,6]</p>
    <p>Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.</p>
    <ol>
        <li>[2, 22, 27, 16, 18, 6] - İlk adımda 2, kendinden önceki elemanlardan daha küçük olduğu için başa eklenir.
        </li>
        <li>[2, 6, 22, 27, 16, 18] - 6, kendinden önceki elemanlardan daha küçük olduğu için başa eklenir.
        </li>
        <li>[2, 6, 16, 22, 27, 18] - 16, kendinden önceki elemanlardan daha küçük olduğu için başa eklenir.
        </li>
        <li>[2, 6, 16, 18, 22, 27] - 18, kendinden önceki elemanlardan daha küçük olduğu için başa eklenir.
        </li>
        <li>[2, 6, 16, 18, 22, 27] - 22, kendinden önceki elemanlardan daha küçük olduğu için başa eklenir.
        </li>
        <li>[2, 6, 16, 18, 22, 27] - 27, kendinden önceki elemanlardan daha küçük olduğu için başa eklenir.
        </li>
    </ol>
    <h3>Big-O Gösterimi:</h3>
    <p>Insertion Sort'un ortalama, en kötü ve en iyi durumdaki zaman karmaşıklığı O(n^2)'dir.</p>
    <h3>Time Complexity:</h3>
    <p>Dizi sıralandıktan sonra 18 sayısı, en kötü durumda (Worst case) O(n) kapsamına girer.</p>
    <ul>
        <li>Average case: O(n^2)
        </li>
        <li>Worst case: O(n^2)
        </li>
        <li>Best case: O(n)
        </li>
    </ul>
 </div>

<div><h2>Selection Sort Aşamaları:</h2>
   <p>Verilen dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]</p>
    <ol>
        <li>[2, 3, 5, 8, 7, 9, 4, 15, 6] - İlk adımda minimum eleman olan 2, dizinin başına getirilir.
        </li>
        <li>[2, 3, 5, 8, 7, 9, 4, 15, 6] - İkinci adımda minimum eleman olan 3, dizinin ikinci sırasına getirilir.
        </li>
        <li>[2, 3, 4, 8, 7, 9, 5, 15, 6] - Üçüncü adımda minimum eleman olan 4, dizinin üçüncü sırasına getirilir.
        </li>
        <li>[2, 3, 4, 5, 7, 9, 8, 15, 6] - Dördüncü adımda minimum eleman olan 5, dizinin dördüncü sırasına getirilir.
        </li>
    </ol>
    <p>Bu adımlar, dizinin Selection Sort'a göre ilk 4 adımını göstermektedir.</p>
</div>

