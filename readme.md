# vscode shortkey
- 동일한 이름의 변수를 한꺼번에 선택하기 (Shift + Ctl + L)

# 주피터노트북(Jupyter notebook)
- shortkey

|shift + enter|해당셀 실행|
|--|--|
|A|위쪽에 셀 추가|
|B|아래쪽에 셀 추가|
|D, D|셀 삭제|
|Y|셀을 코드로 변경|
|M|셀을 마크다운으로 변경|

- 저장파일의 확장자 : *.ipynb(i+python+notebook)


## 마크다운(Markdown)
<!-- 주석 시작    주석 끝-->

2004년 john Gruber + Aaron Swartz
___

밑줄 3개 : 라인 추가

별두개 **두껍게**

별하나 *이탤릭*

물결두개로 감싹 ~~strikethrough~~

### 목록 만들기

* 별표 목록
- 빼기 목록

> 중요한 것은 이렇게 적자

<!-- 링크만들기-->
링크는 이렇게 한다. 대괄호 뒤 소괄호

[요기를 누르면 링크](http://geoarchitect.co.kr)


이미지는 이렇게 한다.

- ![이미지설명](무슨무슨이미지.jpg)
- <img src="이미지 파일 경로 또는 URL" alt="대체 텍스트" width="500" height="300">
   크기를 조정하기위해 사용하는 방법/ 하지만 CSS를 사용하는 것이 좋다.

표만들기
|연번|이름|주소|
|--|--|--|
|001|홍길동|울산시|
|002|성춘향|서울시|
|003|고길동|부산시|


|연번|이름|주소|
|:--|:--:|--:|
|:왼쪽정렬|:가운데정렬:|오른쪽정렬:|
|001|홍길동|울산시|
|002|성춘향|서울시|
|003|고길동|부산시|

코드적어넣기

백틱 `이것은코드다`

백틱3개 코드블록(백틱뒤 언어를 표현하면 하이라이트 됨)
```python
print(type('안녕'))
```
```js
console.log('안녕하시오')
```

github Flavored Markdown


참고 : 마크다운 6분 순삭정리 + 깃허브 리드미 파일 작성팁. 드림코딩