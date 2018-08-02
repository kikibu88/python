# python
#Chapter.1
@(Python with KIKIBU)[Chapter.1]

----------

[TOC]

##파이썬 실행하기
실행방법은 두가지
* 인터렉티브 모드
	* 커맨드 창에 python
	* 간단한 명령어 확인
	* 코드저장 안됨

```bash
$ python
$ >>print 1+1
$ >>2
```
* 커맨드 창에서 파일 실행
	* 파이썬 파일을 작성
			* 커맨드 창에서 python file명
	* 실무에서 자주 사횽

```bash
$ python test.py
```

##print 이용하여 출력하기
```python
print("hello world")
```

##주석
```python
"""
줄바꿈
주석이 가능합니다.
"""

# 한줄 주석
```


##자료형
* int
```python
print(type(123)) // <class 'int'>
```
* float
```python
print(type(12.3)) // <class 'float'>
```
* string
```python
print(type("123")) // <class 'str'>
```
* NoneType
```python
print(type(None)) // <class 'NoneType'>
```

* list, dictionary, tuple 은 추후에

##연산자
### 사칙연산
실제 세계에서 사용하는 일반적인 연산자이다
| 연산자      |    사용예 | 설명  |
| :--: | :--------:| :--: |
| +  | 1+1 // 2 |
| *  | 2*2 // 4 |
| /  | 6/2 // 3 |
| %  | 7%3 // 1 | 나머지 반환 |

###비교연산

| 연산자      | 사용예 | 설명  |
| :---: | :---:| :--: |
| == | a == b |  a와 b가 같다   |
| != |  a!=b |  a와 b가 같지않다  |
| >  |  a > b | a가 b보다 크다  |
| >=  | a >= b | a가 b보다 크거나 같다  |
| <  |  a < b | a가 b보다 작다  |
| <=  | a <= b | a가 b보다 작거나 같다  |


###True, False
비교 연산자의 결과는 참과 거짓으로 돌려준다

```python
print 1==1 // True
print 10>30 // False
print (1+2)!=3 // False
```


###변수 사용하기
```python
temp = 100
print temp // 100
print type(temp) // <type 'int'>

name = "김기범"
print name // 김기범
print type(name) // <type 'string'>

bl = False
print type(bl) // <type 'bool'>

a = 10
b = 20
c = a + b
print a+b // 30
print c // 30
```


