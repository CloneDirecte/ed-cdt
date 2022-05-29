# ed-cdt

📝 Un module Node.js permettant de communiquer facilement à l'API Cahier de textes d'EcoleDirecte.

Utilise simplement axios.

# Installation

```zsh
> npm install ed-cdt
```

# Usage

edCdt fonction

```js
import edCdt from "ed-cdt";

console.log(await edCdt("vrai-utilisateur", "vrai-motdepasse"));
// Output expecté: {code: 200, token: "vrai-token", host: "HTTP66", data: {...}}
```

login fonction

```js
import { login } from "ed-cdt";

console.log(await login("vrai-utilisateur", "vrai-motdepasse"));
// Output expecté: {code: 200, host: "HTTP66", data: {...}}
```

notes fonction

```js
import { cdt } from "ed-cdt";

console.log(await cdt("vrai-token", "vrai-accountId"));
// Output expecté: {code: 200, token: "vrai-token", host: "HTTP66", data: {...}}
```
