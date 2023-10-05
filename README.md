# NextJS x Stripe 
Simple demo app that allows you to purchase a product and fall back into a success or failure page.
## Back-end installation
1. Create a .env file inside stripe-server 
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

## Front End
1. Inside stripe-store type
```bash
npm install
```
2. Run the dev server
```bash
npm run dev
```
