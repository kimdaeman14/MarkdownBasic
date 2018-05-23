# MarkdownBasic

마크다운(Markdown)의 창시자 John Gruber 은 마크다운을 텍스트를 HTML로 변환해 주는 도구라고 정의하고 있다. 쓰기 쉬운 간단한 문법의 텍스트 형식으로 글을 작성하면 HTML의 구조로 변환해 주기 때문에 HTML의 문법을 배우지 않은 사람들도 쉽게 사용할 수 있다. 

> # 헤더
# 가장 큰 제목
## 두번째 큰 제목
### 세번째 큰 제목
#### 네번째 큰 제목
##### 다섯번째 큰 제목
###### 여섯번째 큰 제목

.# 가장 큰 제목
.## 두번째 큰 제목
.### 세번째 큰 제목
.#### 네번째 큰 제목
.##### 다섯번째 큰 제목
.###### 여섯번째 큰 제목

(. 제외)


> # 목록

1. 가나다
2. ABC
3. abc 


- 가나다
  - ABC
- abc 

* 가나다
  * ABC 
* abc 

( -와 *는 같고 공백 두개를 더하면 요렇게 된다)

.1. 가나다
.2. ABC
.3. abc 


.- 가나다
.  - ABC
.- abc 

.* 가나다
.  * ABC 
.* abc 

(. 제외)

> # 강조

큰 바다 넓은 *하늘을 우리는 가졌노라* (2018학년도 _대학수학능력시험_ 필적확인 문구)
: .* 혹은 _으로 감싸준다 (.제외)

큰 바다 넓은 **하늘을 우리는 가졌노라** (2018학년도 대학수학능력시험 필적확인 문구)
: **로 감싸준다

큰 `바다` 넓은 `하늘`을 우리는 가졌노라 (2018학년도 대학수학능력시험 `필적`확인 문구)
: `로 감싸준다

> # 주석
주석은 >기호를 이용하여 작성할 수 있다.
>기호를 이용하여 작성할 수 있다.

> # 링크삽입
[Github](http://github.com/leechoong)를 참고하세요
: []안에는 클릭할이름 ()안에는 웹사이트 주소를 적는다.

> # 이미지삽입
![이미지이름](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/200px-Markdown-mark.svg.png)
![이름](https://c.disquscdn.com/next/embed/assets/img/noavatar92.7b2fde640943965cc88df0cdee365907.png)
![스샷](https://user-images.githubusercontent.com/34432988/39836935-f60d2368-540f-11e8-9e86-8de4e91dd9b5.png)

: ![]안에는 이미지이름 ()안에는 파일위치, 인터넷경로도 포함된다.

> # 표

| 헤더1    |  헤더 2  |   헤더 3  |
|:---|:---:|---:|
| 셀 1    | 셀 2    |   셀 3    |
| 셀 4    | 셀 5    |   셀 6    |
| 셀 7    | 셀 8    |   셀 9    |
| 셀 10   | 셀 11   |   셀 12   |

: 헤더1 사이에는 ||, 셀1 사이에도 ||, 헤더와 셀을 구분하는 구간은 총 3열인데 |:---|:---:|---:| 이런식으로 적는다.


> # 코드블럭
``` 혹은 ~~~ 코드 첫 줄과 마지막 줄에 Back quote ( ` ) 또는 물결( ~ ) 3개 삽입

```
int main(void) {
 printf("Hello, world!\n");
 return 0;
}
```


```
<!-- html -->
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>Insert Code</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
  </body>
</html>
```
