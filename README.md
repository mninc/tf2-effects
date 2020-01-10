# tf2-effects

Up-to-date list of tf2 unusual effects.

```js
const request = require("request");

request("url", function(err, response, body) {
    if (err) console.error(err);
    else {
        let effects = JSON.parse(body);
    }
});
```

```py
import requests
import json

effects = json.loads(requests.get("url").text)
```

You could also check the version and only fetch the effect list when it updates.
