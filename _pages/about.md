---
permalink: /
#title: "About"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<img src="../images/logobyLilia.png" alt="Logo designed by Lilia" style="width: 20%; float: left"> is an incoming Master of Financial Engineering student at the University of California, Berkeley. He holds a master’s degree in quantitative finance from the University of Waterloo and a bachelor’s degree in actuarial science from The University of Hong Kong. Jackie is dedicated to a career in quantitative investment, research or trading, and this is the reason he is moving to the U.S. for a broader market.

Jackie has multiple internship experiences in the financial industry over the past 5 years. Starting as an actuarial intern in Aon and then Swiss Re, he mainly focused on portfolio management with strong analytical and interpersonal skillsets developed. After that, he had a summer internship in Wells Fargo as a quant in the capital markets, where his job was developing deep learning models for derivative pricing. His latest internship was in the largest multi-strategy hedge fund in Toronto under the risk arbitrage team. Cooperated with different teams, Jackie developed automatic Alpha seeking algorithms from M&A and IPO arbitrages.

During his spare time, Jackie likes to act and shot microfilms. He used to be the main actor in the Drama Club and Film Studio of HKU. Jackie was also a volunteer teacher of Beyond the Pivot, which is a Hong Kong-based NGO. He spent a month in Lijiang, Yunnan and taught the elementary school students.

<html>
<head>
<script>
function clickCounter() {
  if (typeof(Storage) !== "undefined") {
    if (localStorage.clickcount) {
      localStorage.clickcount = Number(localStorage.clickcount)+1;
    } else {
      localStorage.clickcount = 1;
    }
    document.getElementById("result").innerHTML = "Jackie is liked " + localStorage.clickcount + " time(s).";
  } else {
    document.getElementById("result").innerHTML = "Sorry, your browser does not support web storage...";
  }
}
</script>
</head>
<body>

<p><button onclick="clickCounter()" type="button">Like !</button></p>
<div id="result"></div>

</body>
</html>
