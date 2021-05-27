[kakao](../../../index.md) / [io.github.kakaocup.kakao.intercept](../../index.md) / [Interceptor](../index.md) / [Configurator](./index.md)

# Configurator

`class Configurator`

Configuration class that is used for building interceptors on the
[Kakao](../../../io.github.kakaocup.kakao/-kakao/index.md) runtime and [Screen](../../../io.github.kakaocup.kakao.screen/-screen/index.md) levels.

**See Also**

[io.github.kakaocup.kakao.Kakao](../../../io.github.kakaocup.kakao/-kakao/index.md)

[io.github.kakaocup.kakao.screen.Screen](../../../io.github.kakaocup.kakao.screen/-screen/index.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `Configurator()`<br>Configuration class that is used for building interceptors on the [Kakao](../../../io.github.kakaocup.kakao/-kakao/index.md) runtime and [Screen](../../../io.github.kakaocup.kakao.screen/-screen/index.md) levels. |

### Functions

| Name | Summary |
|---|---|
| [onDataInteraction](on-data-interaction.md) | `fun onDataInteraction(builder: `[`Interceptor.Builder`](../-builder/index.md)`<DataInteraction, ViewAssertion, ViewAction>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setups the interceptor for `check` and `perform` operations happening through [DataInteraction](#) |
| [onViewInteraction](on-view-interaction.md) | `fun onViewInteraction(builder: `[`Interceptor.Builder`](../-builder/index.md)`<ViewInteraction, ViewAssertion, ViewAction>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setups the interceptor for `check` and `perform` operations happening through [ViewInteraction](#) |
| [onWebInteraction](on-web-interaction.md) | `fun onWebInteraction(builder: `[`Interceptor.Builder`](../-builder/index.md)`<WebInteraction<*>, WebAssertion<*>, Atom<*>>.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Setups the interceptor for `check` and `perform` operations happening through [Web.WebInteraction](#) |