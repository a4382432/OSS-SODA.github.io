# LearningMarkDown
MarkDown 문법을 배우는 시간

## HEADERS
6 가지 크기를 지원 한다.  
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```
## 강조
*이탤릭체*  
**볼드 체**   
_두가지를 **섞어서** 쓸 수 있다._  
~~취소선~~
```
*이탤릭체*   
_이거도 이탤릭체_

**볼드 체**
__이거도 볼드 체__

_두가지를 **섞어서** 쓸 수 있다._  

~~취소선~~
```
## 리스트
### 순서없는 리스트
3단까지 가능하다 탭 한번 입력하면 한단씩 바뀐다 * , - 둘중 맘에드는거 쓰면 됨
* 1번
  * 2번  
    - 3번  
```
* 1번
  * 2번  
    - 3번  
```  
### 순서가 있는 리스트
3단까지 가능하다 탭 두번 입력하면 한단씩 바뀐다 앞에 뭘 입력하든 순서는 바뀌지 않는다.
1. 1번  
3. 2번  
2. 3번  
   1. 4번  
   1. 5번  
      1. 6번  
```
1. 1번  
3. 2번  
2. 3번  
   1. 4번  
   1. 5번  
      1. 6번  
```  
## 인용문
> 인용은 이렇게  
> 보이는 것이고요.
```
> 인용은 이렇게
> 보이는 것이고요.
```
### 수평선
* * *

***

*****

- - -

---------------------------------------
```
* * *

***

*****

- - -

---------------------------------------
```
## 링크
[Markdown 가이드북](https://github.com/OSS-SODA/learningMarkDown)  
<https://github.com/OSS-SODA/learningMarkDown>
```
[Markdown 가이드북](https://github.com/OSS-SODA/learningMarkDown)
<https://github.com/OSS-SODA/learningMarkDown> 
```
## 이미지
아쉽게도 사이즈 조절 기능은 없다.
![이미지](/github-logo.png)
```
![이미지](/github-logo.png)
```
## 코드
### 일반
줄마다 스페이스 네번 혹은 맨앞과 맨뒤에 ` 세번 치면 코드인용이 된다.
```
printf("Hello World\n");
```
    printf("Hello World\n");
    printf("bye\n");
``` 
`X3  
 printf("Hello World\n");  
`X3  
    printf("Hello World\n");
    printf("bye\n");
```
코드 인용처리를  하면 적용되버려서 x3으로 표기하였다.
### 인라인 인용
리눅스환경에서 컴파일시 `./a.out` 파일이 생성됩니다.
```
리눅스환경에서 컴파일시 `./a.out` 파일이 생성됩니다.
```
* * *
## github식 마크다운
### 개행
개행은 라인끝 스페이스 두번이다.
### Syntax highliting
코드인용문 옆에 언어를 적으면 그에맞게 하이라이팅 된다.
```C
//버블소트  
for(i=0;i<5;i++){  
      for(j=0;j<4;j++){  
            if(arr[j]>arr[j+1]){  
                tmp=arr[j];  
                arr[j]=arr[j+1];  
                arr[j+1]=tmp;  
            }  
        }  
    }  
```
```
`X3C
//버블소트  
for(i=0;i<5;i++){  
      for(j=0;j<4;j++){  
            if(arr[j]>arr[j+1]){  
                tmp=arr[j];  
                arr[j]=arr[j+1];  
                arr[j+1]=tmp;  
            }  
        }  
    }  
`X3
```
### 작업목록
체크박스모양으로 표시가 가능하다
- [x] 프로젝트 명세서 짜기
- [ ] 팀원 미팅
```
- [x] 프로젝트 명세서 짜기
- [ ] 팀원 미팅
```
### 표
 보이는그대로 만들면 된다. 
 
 이름 | 벌점  
 ----- | -----  
 황상일 | 0  
 전병모 | 10  
 ```
  이름 | 벌점  
 ----- | -----  
 황상일 | 0  
 전병모 | 10  
 ```
 ### 유저태그
 @3q12
 ```
 @3q12
 ```
