### dispatchAuthStateChangeEvent

When you create custom UI components, `dispatchAuthStateChangeEvent` can be used to change between different auth states e.g. `SignIn`, `ForgotPassword`.

**Usage**

```js
import { AuthState, dispatchAuthStateChangeEvent } from "@aws-amplify/ui-components";

<a onClick={() => dispatchAuthStateChangeEvent(AuthState.SignUp)}>
  Sign up
</a>
```
