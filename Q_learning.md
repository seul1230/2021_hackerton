# π¦ Q-Learning
<br/>
 Q-Learningμ κ°ννμ΅μ ν λ°©λ²μΌλ‘, λ³΄μκ°μ μκ³ μμλ, λͺ©νκΉμ§ λλ¬νλ Qλ₯Ό κ³μ°νμ¬ μ΅μ μ λ£¨νΈλ₯Ό νλ¨νλ€.   <br/><br/>
   


 ![image](https://user-images.githubusercontent.com/86948867/181782592-9743e629-7a5e-45e2-b731-54ccefe4366a.png)
 * * *
μ΄λ, κ°ννμ΅μ State β Actionμ λ°λ₯Έ Rewardκ° μ£Όμ΄μ§λ λ°©μμΌλ‘ μ§νλλ€.
<br/><br/>

β  Q(s,a)λ νμ¬μν(s)μμ aλΌλ νλμ ν λμ κ°

β‘ Q(s',a')λ νμ€ννμμν(s+1)μμ a'λΌλ νλμ ν λμ κ° 

β’ max(Q(s',a'))λ νμ€ννμ μν(s+1)μμ μ»μ μ μλ κ°μ₯ ν° Qκ°μΌλ‘, κ°μ₯ μλ―Έμλ actionμ ν λμ κ°
<br/>
* * *
<br/>
<br/>

κ°λ¨νκ² μ λ¦¬νλ©΄,

> **νμ¬ μνμ Q = λ³΄μ + νμ΅λ₯  * λ€μ μνμμμ μ΅λ Q κ°**

<br/>

λ€μμνμμμ Qκ°μ μκ³ μλ€λ μ μ  νμ νμ¬ μνμ Qλ₯Ό κ΅¬νλ€.

μ¦, μ¬λμ΄ μκ°νλ― μΆλ°μ§λΆν° μ΄λλ‘ κ°μ§ μ νν΄λκ°λκ²μ΄ μλλΌ, μ΅μ’ λͺ©νμ§μ λΆν° κ±°κΎΈλ‘ κ³μ°ν΄μ€λ©° μ΅μ μ κΈΈμ μ°ΎμλΈλ€.
