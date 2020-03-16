Basic Syntax
==========
## Package definition and imports
패키지 상제사항은 소스파일의 맨 위에 위치해야합니다.
<pre>
<code>
// ===Top of the code file===
package my.demo
import kotlin.text.*
</code>
</pre>
디렉토리와 패키지를 일치지킬 필요가 없습니다. 

## Program entry point
코틀린의 진입 점은 main함수입니다.
<pre>
<code>
func main() {
  println("Hello world!")
}
</code>
</pre>

## Functions
함수는 다음과 같이 작성합니다.

<pre>
<code>
func 함수 이름 (파라미터1: 입력 타입, ... ): 반환 타입 {
  return 반환 값
}
</code>
</pre>

함수의 바디 없이 바로 반환 할 수도 있습니다.

<pre>
<code>
func sum(a: Int, b: Int)  {
  return a + b
}
</code>
</pre>

<pre>
<code>
func sum(a: Int, b: Int) = a + b
</code>
</pre>

## Variables
Read-only 로컬 변수들은 ```val''''로 정의됩니다. 

