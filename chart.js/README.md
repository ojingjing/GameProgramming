

# ๐ฐ Use Chart.js
___
### USE chart
**1.Bubble chart**   
**2.Doughnut chart**   
**3.Line chart**   

___
### set up Chart.js  
html ์ chart ๋ฅผ ์ฐ๊ธฐ์ํด์๋ ์ธํ์ ํด์ฃผ์ด์ผํ๋ค.  
js์ข๋ฅ์ฌ์ script๋ฅผ ์ด์ฉํ์ฌ์ผํ๋ค.  
**canvas** ๋ฅผ ์ด์ฉํ์ฌ ์ฐจํธ๋ฅผ ๋ถ๋ฌ์์ค๋ค.     
**body**์์ ์จ์ผํ๋ค.  
```
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.5.0/Chart.min.js"></script>
    <canvas id="bubble-chart" width="800" height="800"></canvas>
    <canvas id="doughnut-chart" width="800" height="450"></canvas>
    <canvas id="line-chart" width="800" height="450"></canvas>
    
```
___
### chart   

Bubble chart: mbti๋ณ ์ฑ๊ฒฉ  

Doughnut chart: ํ์กํ๋ณ ์ธ๊ธฐ์์  

Line chart: My life graph ๋ฅผ ๊ตฌํํ์๋ค.

 ___
### Improvement   
์ฐ์  bubble chart  ์์ x์ถ์ ๋ณด๋ฉด ์นธ์ ํฌ๊ธฐ๊ฐ 80์ผ๋ก ๋ค๋ฅธ๊ฑธ ์ ์ ์๋ค.
์ด๋ถ๋ถ์ ๊ฐ์ ํ๊ธฐ ์ํด์ options์
```
  ticks:{min:-100 , max:100}
```
์ผ๋ก ์นธ๊ฐ์๋ฅผ 100์ผ๋ก ๋ง์ถฐ๋ณผ๋ คํ์ง๋ง ํ๋ฉด์ด ์์ ๋จ์ง์์๋ค...

```
    responsive:false
```
๋ฅผ ์จ์ ๋ฐ๊ฟ๋ณด๋ผ๋ ๋ง๋ ์์๋๋ฐ ์ด๊ฒ๋ ์์๊ฐ์ด ํ๋ฉด์ด ๋จ์ง์์๋ค..
### webHosting
>[netlify](https://loquacious-cuchufli-e1c176.netlify.app/)
