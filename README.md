# CSS3

### 웹 페이지 구성
→ 문서 내용 작성과 꾸미는 부분을 분리하여 내용을 수정해도 디자인을 바꿀 필요가 없고 디자인을 수정해도 글 내용을 바꿀 필요가 없음  
다양한 기기에도 디자인만 따로 적용하여 구동시킬 수 있음

![image](https://user-images.githubusercontent.com/59958929/103136858-5d43ce00-4707-11eb-9a2b-afc10f77b1ca.png)

### style과 stylesheet
→ style은 정해진 속성을 입력하여 웹 페이지를 꾸미는 것 
stylesheet는 웹 페이지에서 반복적으로 쓰는 style을 모아놓은 것
![image](https://user-images.githubusercontent.com/59958929/103136860-63d24580-4707-11eb-802d-aa5cb6abdacf.png)

### CSS 적용
<b>내부 스타일 시트</b>
→ <style></style> 내부에 스타일 정보를 저장하는 방법
```
<style>
p{text-align: center;}
</style>
```
<b>외부 스타일 시트</b>
→ <link>태그를 이용하여 css파일을 읽어와서 스타일 적용
```
<link href=“css파일경로” rel=“stylesheet” type=“text/css”>
```

<b>인라인 스타일 시트</b>
→ 태그 내부에 스타일 정보를 지정하는 방법
```
<html>
<head></head>
<body>
<p style=“스타일정보;”>
</body>
</html>
```
