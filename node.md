

# Install node 9.11.1
Link: https://nodejs.org/en/

$ node -v
v9.11.1

$ npm -v
5.6.0

# npm set proxy
$ npm config set proxy http://web-proxy.xx.xx.com:8080
$ npm config set https-proxy http://web-proxy.xx.xx.com:8080

# npm unset proxy
npm config delete proxy
npm config delete https-proxy
npm config list
