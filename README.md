# Cross-leaks 検知ツール


検知ツール


## 使用方法
1. Clone the repository
2. Change cross-origin domain in config.js
    - for local testing: let baseUrl = 'http://localhost:8000/'
3. Build javascript: `npm install && npm run build`
4. Get cert with 
   `certbot certbot certonly --standalone --cert-name "xsinator.com" -d "xsinator.com" -d "xsinator.xyz" -d "crossorigin.xsinator.xyz" --register-unsafely-without-email`
5. docker-compose up
## APRIL 4月


