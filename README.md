# Crunchiemeltz
Shopify website template code

## how to log in 

### Step 1: Install all packages
npm install -g @shopify/cli@latest

### Step 2: Log into shopify and copy the store ID from the URL you get
https://admin.shopify.com/store/bbf1a8-02
Use only the ID at the back of the link : 'bbf1a8-02'

### Step 3: Logout
shopify auth logout

### Step 4: Pull the theme using URL with .myshopify.com instead of your domain, even if you have your own one linked
shopify theme pull --store=bbf1a8-02.myshopify.com --path=./

### How to start
type "shopify theme dev" in terminal