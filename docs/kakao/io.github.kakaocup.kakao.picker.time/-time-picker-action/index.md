[kakao](../../index.md) / [io.github.kakaocup.kakao.picker.time](../index.md) / [TimePickerAction](./index.md)

# TimePickerAction

`interface TimePickerAction : `[`BaseActions`](../../io.github.kakaocup.kakao.common.actions/-base-actions/index.md)

Provides actions for time picker

### Inherited Properties

| Name | Summary |
|---|---|
| [view](../../io.github.kakaocup.kakao.common.actions/-base-actions/view.md) | `abstract val view: `[`ViewInteractionDelegate`](../../io.github.kakaocup.kakao.delegate/-view-interaction-delegate/index.md) |

### Functions

| Name | Summary |
|---|---|
| [setTime](set-time.md) | `open fun setTime(hour: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, minutes: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`ViewInteractionDelegate`](../../io.github.kakaocup.kakao.delegate/-view-interaction-delegate/index.md)<br>Set time to picker dialog |

### Inherited Functions

| Name | Summary |
|---|---|
| [act](../../io.github.kakaocup.kakao.common.actions/-base-actions/act.md) | `open fun act(function: () -> ViewAction): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Performs custom action on a view |
| [click](../../io.github.kakaocup.kakao.common.actions/-base-actions/click.md) | `open fun click(location: GeneralLocation = GeneralLocation.VISIBLE_CENTER): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Performs click on view |
| [doubleClick](../../io.github.kakaocup.kakao.common.actions/-base-actions/double-click.md) | `open fun doubleClick(location: GeneralLocation = GeneralLocation.VISIBLE_CENTER): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Performs double click on view |
| [longClick](../../io.github.kakaocup.kakao.common.actions/-base-actions/long-click.md) | `open fun longClick(location: GeneralLocation = GeneralLocation.VISIBLE_CENTER): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Performs long click on view |
| [onFailure](../../io.github.kakaocup.kakao.common.actions/-base-actions/on-failure.md) | `open fun onFailure(function: (error: `[`Throwable`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-throwable/index.html)`, matcher: Matcher<`[`View`](https://developer.android.com/reference/android/view/View.html)`>) -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Adds failure handler to the view |
| [pressImeAction](../../io.github.kakaocup.kakao.common.actions/-base-actions/press-ime-action.md) | `open fun pressImeAction(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Presses IME action, if supported view is in focus |
| [repeatUntil](../../io.github.kakaocup.kakao.common.actions/-base-actions/repeat-until.md) | `open fun repeatUntil(maxAttempts: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 1, action: () -> ViewAction, matcher: `[`ViewBuilder`](../../io.github.kakaocup.kakao.common.builders/-view-builder/index.md)`.() -> `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Repeats given action on the view until this view will match the given matcher |
| [scrollTo](../../io.github.kakaocup.kakao.common.actions/-base-actions/scroll-to.md) | `open fun scrollTo(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Scrolls to the view, if possible |

### Inheritors

| Name | Summary |
|---|---|
| [KTimePicker](../-k-time-picker/index.md) | `class KTimePicker : `[`KBaseView`](../../io.github.kakaocup.kakao.common.views/-k-base-view/index.md)`<`[`KTimePicker`](../-k-time-picker/index.md)`>, `[`TimePickerAction`](./index.md)`, `[`TimePickerAssertion`](../-time-picker-assertion/index.md)<br>View for interact with default time picker |