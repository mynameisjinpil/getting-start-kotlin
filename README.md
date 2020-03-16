# getting-start-kotlin
// TODO: Anotation processing, Data binding, Dagger알아보기

Laguage Guide<https://kotlinlang.org/docs/reference/>

Tutorials<https://kotlinlang.org/docs/tutorials/>

**Language Guide**

## Using Kotlin for Android Development

코틀린은 안드로이드를 개발하기에 적합하다.  새로운 제약사항 없이 모던 랭귀지의 장점을 안드로이드에 가져올 수 있다.

- Compatibility: 코틀린은 jdk6에 딱 떨어진다. 코틀린 어플리케이션이 오래된 안드로이드 디바이스에서 문제없이 작동할 것이라 확신한다. 코틀린 툴링은 안드로이드 스튜디오 에서 완벽하게 지원되며 안드로이드 빌드 시스템과 호환됩니다.

- Performance: 코틀린 어플리케이션은 자바만큼 빠르게 작동합니다.  왜냐하면 매우 유사한 바이트 코드 구조를 가지기 때문입니다. 코틀린의 인라인 펑션 지원을 사용한 코드는 람다를 실행할 때 종종 자바보다 더 빠르기도 합니다.

- Interoperability: 코틀린은 모든 안드로이드 라이브러리 지원을 허용하며 완벽하게 자바와 호환됩니다. 이것은 어노테이션 프로세싱과 데이터 바인딩, Dagger도 포함합니다.


-  Foot Print: 코틀린은 매우 간단한 런타임 라이브러리를 가집니다. 이것은 ProGuard를 이용해 더 줄일수도 있습니다. 실제 어플리케이션에서 코틀린 런타임은 추가합니다 오직 몇백개의 메서드와 100k 이하 사이즈의 .apk 파일들을.

- Compilation Time: 코틀린은 지원합니다 효율적인 컴파일의 증가를. 그래서 깨끗한 빌드에는 오버해드가 약간 있지만 incremental builds는 대게 자바보다 빠릅니다.

- Learning Curve: 자바 개발자는 시작합니다 코틀린을 매우 쉽게. 자바를 자동으로 코틀린으로 바꿔주는 컨버터가 코틀린 플러그인에 포함되어 있습니다. 

## Steps

1. Download and install [Android Studio][https://developer.android.com/studio/index.html] which includes Kotilin support out of box.

2. Follow the [Getting Started with Android and Kotlin][https://kotlinlang.org/docs/tutorials/kotlin-android.html] tutorial to create your first Kotlin apllication

3. For a more in-depth introduction, check out the [reference documentation][https://kotlinlang.org/docs/reference/] and [Kotlin Koands][https://kotlinlang.org/docs/tutorials/koans.html].


