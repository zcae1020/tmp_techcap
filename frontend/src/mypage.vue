<template>
    <div>
        <div id="top">
      <a href="/">
          <img id="logo" width=150px height=150px src='@/assets/logo.png'>
        </a>
          <div id="t1">
            <a href = "/mypage">
              <img id="emo1" src="@/assets/emo.png">
              <p id="mypage">마이페이지</p>
            </a> 
          </div>
          <div v-on:mouseover="greet" v-on:mouseout="out">
            <div id="t2">
              <a href="/aim"><button class="bt" id="bt1">교봉 단체 정보</button></a>
              <a href="/match"><button class="bt" id="bt2">선생님</button></a>
              <a href="/teacherApply"><button class="bt" id="bt3">학생</button></a>
              <a href="/info"><button class="bt" id="bt4">공지사항</button></a>
            </div>

            <div id ="t3">
              <p class="li1" id="bt_kyobong">
                <a href="/aim">설립목적</a><br>
                <a href="/select">선정기준</a>
              </p>
              <p class="li1" id="bt_teacher">
                <a href="/match">학생 매칭하기</a><br>
                <a href="/studentApply">학생 신청 리스트</a>
              </p>
              <p class="li1" id="bt_student">
                <a href="/teacherApply">선생님 신청 리스트</a>
              </p>
              <p class="li1" id="bt_notice">
                <a href="/info">공지사항</a><br>
                <a href="/example">우수사례</a><br>
                <a href="/file">첨부파일</a>
              </p>
              </div>
          </div>
      </div>
        <div id="body">
            <button id="home" class="btn">홈</button>
            <button id="inform" class="btn">내 정보 변경</button>
            <button id="secure" class="btn">보안</button>
            <button id="class" class="btn">내 수업</button>
            <button id="student" class="btn">내 학생</button>
            <button id="teacher" class="btn">내 선생님</button>
            <button id="home" class="btn">홈</button>
            <button id="inform" class="btn">내 정보 변경</button>
            <button id="secure" class="btn">보안</button>
            <button id="class" class="btn">내 수업</button>
            <button id="student" class="btn">내 학생</button>
            <button id="teacher" class="btn">내 선생님</button>
            <a href="/aim">
                <h1 id="mp">마이페이지</h1>
            </a>
            <img id="image" src="@/assets/image.png">
           
        </div>

    </div>
</template>

<script>
    
</script>
<style> 
    #mp{
        font-size: 50px;
        position: absolute;
        left: 800px;
        top: 500px;
        color: black;
    }
    #image{
        width: 200px;
        height: 200px;
        position: absolute;
        left: 818px;
        top: 200px;
    }
    .btn{
        width: 200px;
        height: 50px;
        position: absolute;
        left: 50px;
        background-color: white;
        font-size: 20px;
    }
    #home{
        top:250px;
    }
    #inform{
        top: 300px;
    }
    #secure{
        top: 350px;
    }
    #class{
        top: 400px;
    }
    #student{
        top: 450px;
    }
    #teacher{
        top: 500px;
    }
</style>