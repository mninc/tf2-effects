# tf2-effects

Up-to-date list of tf2 unusual effects.

```js
const request = require("request");

request("https://raw.githubusercontent.com/mninc/tf2-effects/master/effects.json", function(err, response, body) {
    if (err) console.error(err);
    else {
        let effects = JSON.parse(body);
    }
});
```

```py
import requests
import json

effects = json.loads(requests.get("https://raw.githubusercontent.com/mninc/tf2-effects/master/effects.json").text)
```

You could also check the [version](https://raw.githubusercontent.com/mninc/tf2-effects/master/__version__) and only fetch the effect list when it updates.
