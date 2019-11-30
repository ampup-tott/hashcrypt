# hashcrypt
## Install via npm 
```
npm install hashcrypt --save
```
## Install via yarn
```
yarn add hashcrypt
```
## Usage
```javascript
const hashscrypt = require('hashcrypt');
```
### To hash a password
```javascript
const hashPass = hashcrypt.hash(password);
```
### To Check password
```javascript
const isValid = hashcrypt.compare(password, hashPass);
```