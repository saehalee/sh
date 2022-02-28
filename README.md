# Read.me 사용법

## 1. Header
```
# first header
## second header
### third header
#### four-th header
##### five-th header
###### six-th header
```
# first header
## second header
### third header
#### four-th header
##### five-th header
###### six-th header

## 2. BlockQuote
```
> first blockquote.
>> second blockquote.
>>> third blockquote.
>>>> four-th blockquote.
>>>>> five-th blockquote.
>>>>>> six-th blockquote.
```
> first blockquote.
>> second blockquote.
>>> third blockquote.
>>>> four-th blockquote.
>>>>> five-th blockquote.
>>>>>> six-th blockquote.

## 3. 목록
### 3-1. 순서있는 목록
```
1. first
2. second
3. third
```
1. first
2. second
3. third
### 3-2. 글머리 기호 목록
```
* 상위목록
    * 중위목록 
        * 하위목록

+ 상위목록
    + 중위목록
        + 하위목록

- 상위목록
    - 중위목록 
        - 하위목록

* 혼합상위목록
    + 혼합중위목록 
        - 혼합하위목록
```
* 상위목록
    * 중위목록 
        * 하위목록

+ 상위목록
    + 중위목록
        + 하위목록

- 상위목록
    - 중위목록 
        - 하위목록

* 혼합상위목록
    + 혼합중위목록 
        - 혼합하위목록

## 4. code
* 4칸의 공백 또는 한번의 Tab키로 들여쓰기를 하면 변환되어 들여쓰지 않는 행까지 계속 된다.
```
code block start:   
    function(){   
        code block.   
    }       
end code block.
```

code block start:    
    function(){ 
        code block. 
    }     
end code block.
* `<pre><code>{code}</code></pre>` 를 사용하여 코드블럭을 나타낼 수도 있다.
```
<pre>
<code>
function(){
	code block.	
}
</code>
</pre>
```
<pre>
<code>
function(){
	code block.	
}
</code>
</pre>
* __```__ 을 사용하여 코드블럭을 나타내기도 한다.
<pre>
<code>
    ```
    function(){
	    code block.
    }
    ```
</code>
</pre>
* __```__ 시작점에 사용하는 언어를 선언하여 문법강조(Syntax highlighting)이 가능하다.
<pre>
<code>
```java
public class Hello {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
</code>
</pre>
```java
public class Hello {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

## 5. 구분선/수평선
페이지 나누기 용도로 많이 사용한다.
```
# Header
* first
 + second
  - third
-------------------------------------------------------
###### horizon
```
# Header
* first
 + second
  - third
-------------------------------------------------------
###### horizon

## 6. Link
* 참조링크
```
Link: [Google][googlelink]   
[googlelink]: https://google.com "Go google"
```
Link: [Google][googlelink]    
[googlelink]: https://google.com "Go google"
+ 외부링크
```
사용문법: [Title](Link)   
적용예시: [Google](https://google.com, "google link")
```
사용문법: [Title](Link)    
적용예시: [Google](https://google.com, "google link")
- 자동연결
일반적인 URL 또는 이메일주소인 경우 사용한다.
```
* 외부링크 : <https://github.com/saehalee/sh>
* e-mail : <seaha0110@naver.com>
```
* 외부링크 : <https://github.com/saehalee/sh>    
* e-mail : <seaha0110@naver.com>
## 7. 강조
문장 중간에 사용할 경우에는 띄어쓰기를 사용하는 것이 좋다.
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
문장 중간에 사용할 경우 **띄어쓰기** 를 사용하는 것이 좋다.
```
*single asterisks*    
_single underscores_    
**double asterisks**    
__double underscores__    
~~cancelline~~    
문장 중간에 사용할 경우 **띄어쓰기** 를 사용하는 것이 좋다.

## 8. 이미지
```
![Alt text](/path/to/img.jpg)
```
![Alt text](/path/to/img.jpg)
위 방법은 사이즈 조절 기능이 없으므로  `<img width=”” height=””></img>` 를 이용한다.
```
<img src="/path/to/img.jpg" width=450px height=300px alt="image"></img>
```
<img src="/path/to/img.jpg" width=450px height=300px alt="image"></img>

## 9. 줄바꿈
3칸 이상 띄어쓰기를 하면 줄이 바뀐다.
```
줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.   이렇게
```
줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.   이렇게

출처:[공통] 마크다운 markdown 작성법 <https://gist.github.com/ihoneymon/652be052a0727ad59601>