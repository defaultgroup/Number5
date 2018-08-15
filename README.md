<html>
<style>
body{
  background-color: powderblue;
  text-align: center;
}
h2{
  color:green;
}
button{
  background-color:#000000
  color:#FFFFFF;
}
button:hover{
  text-decoration: underline;
  background-color: white;
  color: #FF0000;
}

</style>
<body>

<h2>문제 시작!</h2>

<p>5. 다음문제에 대한 정답을 골라 <strong>알맞은</strong> 버튼을 누르세요</p>
<img src="http://mblogthumb1.phinf.naver.net/20161015_212/kangyu718_1476534601188RBDeE_PNG/16_%BC%F6%C6%AF_%B9%B01_p.50_7%B9%F8.png?type=w2" alt="수능특강 물리 문제에 대한 이미지 검색결과" onload="typeof google==='object'&amp;&amp;google.aft&amp;&amp;google.aft(this)" width="304" height="350" style="margin-top: 2px;">
<br>
<br>
<br>
<input type="button" value="1번" onclick="alert('N')">  &emsp;&emsp;&emsp;&emsp;
<input type="button" value="2번" onclick="alert('Q')">  &emsp;&emsp;&emsp;&emsp;
<input type="button" value="3번" onclick="alert('U')">  &emsp;&emsp;&emsp;&emsp;
<input type="button" value="4번" onclick="alert('P')">  &emsp;&emsp;&emsp;&emsp;
<input type="button" value="5번" onclick="alert('E')">
  <br>
  <br>
  <button onclick="hint()">힌트</button>
  <p id="hint"></p>
  <script>
  function hint() {
      var txt;
      if (confirm("힌트를 보시겠습니까? 진짜로? 정말?")) {
          txt = "빠르게 움직이는 물체를 볼때 빠르게 움직이는 물체의 시간은 느리게 보이고 길이는 운동방향과 나란한 방향으로 수축해보입니다!";}
          else {
          txt = "뭐... 안보면 말고 모를까봐 넣어봤지...";
      }
      document.getElementById("hint").innerHTML = txt;
  }
  </script>
<a href="https://defaultgroup.github.io/Number6/"> <button> 다음문제로! </button></a> &nbsp; &nbsp;
<a href="https://defaultgroup.github.io/START/" id="first"> <button> 처음으로! </button></a> &nbsp; &nbsp;
<a href="https://defaultgroup.github.io/END/" id="final"> <button> 최종정답으로! </button></a>
</body>
</html>
