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

#### 적용예
# first header
## second header
### third header
#### four-th header
##### five-th header
###### six-th header
*****

## 2. BlockQuote
```
> first blockquote.
>> second blockquote.
>>> third blockquote.
>>>> four-th blockquote.
>>>>> five-th blockquote.
>>>>>> six-th blockquote.
```

#### 적용예
> first blockquote.
>> second blockquote.
>>> third blockquote.
>>>> four-th blockquote.
>>>>> five-th blockquote.
>>>>>> six-th blockquote.
*****
## 3. 목록
### 3-1. 순서있는 목록
```
1. first
2. second
3. third
```

#### 적용예
1. first
2. second
3. third
*****
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

#### 적용예
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
*****

## 4. code
* `<pre><code>{code}</code></pre>` 를 사용하여 코드블럭을 나타낸다.
```
<pre>
<code>
function(){
	code block.	
}
</code>
</pre>
```

#### 적용예
<pre>
<code>
function(){
	code block.	
}
</code>
</pre>
*****
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

#### 적용예
```
function(){
    code block.
}
```
*****
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

#### 적용예
```java
public class Hello {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
*****

## 5. 구분선/수평선
페이지 나누기 용도로 많이 사용한다.
```
* * *
***
*****
- - -
---------------------------------------------
###### horizon
```
#### 적용예
* * *
***
*****
- - -
---------------------------------------------
###### horizon

## 6. Link
* 참조링크
```
[link keyword][id]

[id]: URL "Optional Title here"

// code
Link: [Google][googlelink]   

[googlelink]: https://google.com "Go google"
```

#### 적용예
Link: [Google][googlelink]

[googlelink]: https://google.com "Go google"
*****
+ 외부링크
```
사용문법: [Title](Link)   
적용예시: [Google](https://google.com, "google link")
```

#### 적용예
Link: [Google](https://google.com, "google link")
*****
- 자동연결    
일반적인 URL 또는 이메일주소인 경우 사용한다.
```
외부링크 : <https://github.com/saehalee/sh>
e-mail : <seaha0110@naver.com>
```

#### 적용예
외부링크 : <https://github.com/saehalee/sh>    
e-mail : <seaha0110@naver.com>
*****

## 7. 강조
```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
문장 중간에 사용할 경우 **띄어쓰기** 를 사용하는 것이 좋다.
```
#### 적용예
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
#### 적용예
![coding](https://images.unsplash.com/photo-1461749280684-dccba630e2f6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1469&q=80)
*****
위 방법은 사이즈 조절 기능이 없으므로  `<img width=”” height=””></img>` 를 이용한다.
```
<img src="/path/to/img.jpg" width=450px height=300px alt="image"></img>
```
#### 적용예
<img src="https://images.unsplash.com/photo-1461749280684-dccba630e2f6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1469&q=80" width=450px height=300px alt="coding"></img>

## 9. 줄바꿈
3칸 이상 띄어쓰기를 하면 줄이 바뀐다.
```
줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.    이렇게
```

#### 적용예
줄 바꿈을 하기 위해서는 문장 마지막에서 3칸이상을 띄어쓰기해야 한다.    
이렇게
***
출처:[공통] 마크다운 markdown 작성법 <https://gist.github.com/ihoneymon/652be052a0727ad59601>