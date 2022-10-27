# html_1027  
  
  
  
  
  
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/198170350-8e401ba4-6947-4f48-8a33-06d4ff7a0ec9.png)
  

submit-폼태그의 액션 속성으로 이동하라..  
클라이언트가 요청할때 서버에게 전달해야하는것 두가지-어떠한 요청인지(액션)과 데이터 값  
데이터값을 전송하는 방법 두가지 -get방식    
                              post방식  
  
  
액션은 - ?표 앞에 있는것 test  
변수명은 - ?표 뒤에있는것 nname  
값은 파라미터라고 한다.  
  
  
  
  
  
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>04</title>
</head>
<style>


</style>

<body>
    <form action="joinUser" method="get">
        <table border="1">
            <tr>
                <th colspan="4">회원가입</th>
            </tr>
            <tr>
                <th><label for="id">아이디</label></th>
                <td colspan="2"><input id="id" type="text" name="id"></td>
                <th><input type="submit" value="중복검사"></th>
            </tr>
            <tr>
                <th><label for="pwd">비밀번호</label></th>
                <td colspan="3"><input type="password" name="password" value=""></td>

            </tr>
            <tr>
                <th><label for="pwdc">비밀번호확인</label></th>
                <td colspan="3"><input type="password" name="passwordC"></td>

            </tr>
            <tr>
                <th><label for="name">이름</label></th>
                <td colspan="3"><input id="name" type="text" name="name"></td>

            </tr>
            <tr>
                <th>성별</th>
                <td>
                    <input id="man" type="radio" name="gender" value="m">
                    <label for="man">남자</label>
                    <input id="woman" type="radio" name="gender" value="w">
                    <label for="woman">여자</label>
                </td>
            </tr>
            <tr>
                <th>전화번호</th>
                <td colspan="1">010</td>
                <td colspan="1"><input id=" num" type="text" name="tel1" value=""></td>
                <td colspan="1"><input id=" num" type="text" name="tel2" value=""></td>

            </tr>
            <tr>
                <th>희망등급</th>
                <td colspan="1">
                    <select name="grade"> <!--한개만 선택했을때 value로 지정한것이 값이 된다-->
                        <option value="g1">1등급</option>
                        <option value="g2">2등급</option>
                        <option value="g3">3등급</option>

                    </select>
                </td>
                <th colspan="2">심사후 등급이 결정됩니다</th>
            </tr>
            <tr>
                <th colspan="4">*약관에 동의합니다</th>
            </tr>
            <tr>
                <th>관심사항</th>
                <td colspan="3">  <!--쳌박스는 이름이같아도 다중선택이 된다 .이것을 자동으로 배열로 만들어줌-->
                    <input type="checkbox" name="hby" value="스"> 스포츠
                    <input type="checkbox" name="hby" value="여"> 여행
                    <input type="checkbox" name="hby" value="독"> 독서

                    
                </td>
            </tr>
            <tr>
                <th>관심지역</th>
                <td colspan="3">
                    <select multiple="multiple" name="likeCity">
                        <option value="경기">경기</option>
                        <option value="충남">충남</option>
                        <option value="충북">충북</option>
                        <option value="대전">대전</option>
                        <option value="부산">부산</option>
                    </select>
                </td>
            </tr>
            <tr>
                <td colspan="3"><input type="file" name="file" value="file"></td>
            </tr>
            <tr>
                <th colspan="2"><input type="reset" value="reset"></th>
                <th colspan="2"><input type="submit" value="save"></th>
            </tr>
        </table>
    </form>
</body>

</html>
```   
  
  
  
  
  
  
  
valu=""는 url에 돌아가는 값 (직접 입력하지 않을경우에)  
->    http://127.0.0.1:5500/joinUser?id=aaa&password=1111&passwordC=1111&name=%EA%B9%80%ED%95%98%EC%98%81&gender=w&tel1=7132&tel2=6837&grade=g3&hby=%EC%97%AC&hby=%EB%8F%85&file=
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/198199575-139c7272-fbcb-49ee-9c2d-0204a8c6f1bf.png)

  
  
  
  
  
  
-------------------------------------------  
  
  
  
  
  
###css  
  
  
  
헤드사이에 많이 둠  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/198205765-ada1bc6c-a079-47bf-bd3d-5743fced2da2.png)
  
  
  
id는 유니크해야 정상  
  
  
  
  
  
  
  
  
  
  
  
  
![image](https://user-images.githubusercontent.com/80766275/198207521-06c32680-21f0-4441-ade9-26cd2eaf8970.png)
  
  
  
  

  
  


  
