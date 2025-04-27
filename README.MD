#### Passcode Input - OAuth

1. Installation
```
npm i passcode-input
```

2. Import & use
```
import { PasscodeInput } from "passcode-input";

const [isLoginPassOpen, setIsLoginPassOpen] = useState(false);


<PasscodeInput isLoginPassOpen={isLoginPassOpen} setIsLoginPassOpen={setIsLoginPassOpen} />
```