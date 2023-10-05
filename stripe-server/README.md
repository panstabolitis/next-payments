## Back-End Installation
1. Create a .env file inside stripe-server (this folder)
```bash
touch .env
```

and then add your test key or real key ```STRIPE_SECRET_KEY=sk_test...```

2. Install the required packages 

```bash
npm install
```
3. Turn on the server! (Default Port: 4242)
```bash
node src/index.js
```