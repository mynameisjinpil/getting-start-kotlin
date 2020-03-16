Basic Syntax
==========
## Package definition and imports
패키지 상제사항은 소스파일의 맨 위에 위치해야합니다.

```
// ===Top of the code file===
package my.demo
import kotlin.text.*
```
디렉토리와 패키지를 일치지킬 필요가 없습니다. 

## Program entry point
코틀린의 진입 점은 main함수입니다.

```
func main() {
  println("Hello world!")
}
```

## Functions
함수는 다음과 같이 작성합니다.

```
func 함수 이름 (파라미터1: 입력 타입, ... ): 반환 타입 {
  return 반환 값
}
```
함수의 바디 없이 바로 반환 할 수도 있습니다.

```
func sum(a: Int, b: Int)  {
  return a + b
}
```

```
func sum(a: Int, b: Int) = a + b
```
## Variables
Read-only 로컬 변수들은 `val`로 정의됩니다. 값은 한번만 할당 

```
val a: Int = 1 // immediate assignment
val b = 2 // int type is inderred
val c: Int // type required when no initializer is provided
c = 3 // deffered assignment
```

변수는 `var`키워드를 사용했을 때 수정해 줄 수 있다.

```
var x += 5
x += 1
```

최상위 레벨 변수.

```
val PI = 3.14
var x = 0

func incrementX() {
	x += 1
}
```