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
<button onclick="document.getElementById('myImage').src='https://postfiles.pstatic.net/MjAxODA3MzBfMTQw/MDAxNTMyOTQ5OTc1ODQx.R91xbbwDZbniiwFFXH3n0mbWNUzvQwEJ13FD7wLGliwg.56wB_jFrWgJiA0_N09ps760ny2P3ozAym5dTQ7FVqmog.PNG.ychh1123/bad-face_%281%29.png?type=w580'">
  <strong>1번</strong></button>
  &emsp;&emsp;&emsp;&emsp;
<button onclick="document.getElementById('myImage').src='https://postfiles.pstatic.net/MjAxODA3MzBfMTQw/MDAxNTMyOTQ5OTc1ODQx.R91xbbwDZbniiwFFXH3n0mbWNUzvQwEJ13FD7wLGliwg.56wB_jFrWgJiA0_N09ps760ny2P3ozAym5dTQ7FVqmog.PNG.ychh1123/bad-face_%281%29.png?type=w580'"><strong>2번</strong></button>
&emsp;&emsp;&emsp;&emsp;
<button onclick="document.getElementById('myImage').src='https://postfiles.pstatic.net/MjAxODA3MzBfNjgg/MDAxNTMyOTQ5ODQ3OTIx.M3hgYCFu0UAXKYMn4bS_9_Jw3W4_xn906O2cqD0KjVUg.gFvKThE0Hwa_JEAcQ55Gs0VnNKgFMAo84uQUhqdVrasg.PNG.ychh1123/hand.png?type=w580'"
><strong>3번</strong></button>
&emsp;&emsp;&emsp;&emsp;
<button onclick="document.getElementById('myImage').src=' https://postfiles.pstatic.net/MjAxODA3MzBfMTQw/MDAxNTMyOTQ5OTc1ODQx.R91xbbwDZbniiwFFXH3n0mbWNUzvQwEJ13FD7wLGliwg.56wB_jFrWgJiA0_N09ps760ny2P3ozAym5dTQ7FVqmog.PNG.ychh1123/bad-face_%281%29.png?type=w580'">
  <strong>4번</strong></button>
&emsp;&emsp;&emsp;&emsp;
<button onclick="document.getElementById('myImage').src='https://postfiles.pstatic.net/MjAxODA3MzBfMTQw/MDAxNTMyOTQ5OTc1ODQx.R91xbbwDZbniiwFFXH3n0mbWNUzvQwEJ13FD7wLGliwg.56wB_jFrWgJiA0_N09ps760ny2P3ozAym5dTQ7FVqmog.PNG.ychh1123/bad-face_%281%29.png?type=w580'">
  <strong>5번</strong></button>
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
</body>
</html>
