# Binance-Bot
Another bot for Binance with the fewer code possible, for an automatic buying and selling based on MACD, RSI and Stochastic indicators

### Installation
#### redis-server
```bash
sudo apt-get install redis

redis-cli flushall
sudo /etc/init.d/redis-server stop
sudo mcedit /etc/redis/redis.conf 

| #save 900 1
| #save 300 10
| #save 60 10000

sudo rm /var/lib/redis/dumb.db
sudo /etc/init.d/redis-server start
```
#### node-js
```bash
npm install chalk
npm install moment
npm install node-binance-api
npm install redis
npm install tulind
```

### License

MIT License

Copyright (c) May 1, 2018 Emmanuel CHARETTE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
