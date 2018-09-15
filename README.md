# chrome-driver-taobao-mirrors-proxy

While http://npm.taobao.org/mirrors/chromedriver/ mirrors http://chromedriver.storage.googleapis.com/, 
the mirror has no xml file described chromedrivers 


This is a proxy to http://npm.taobao.org/mirrors/chromedriver/ which can reponse xml file.

This is very convenient for angualr e2e test.

## usage

### pull and run image
```

docker pull fanyinmeng/chrome-driver-taobao-mirrors-proxy

docker run -p 80:80 -d fanyinmeng/chrome-driver-taobao-mirrors-proxy

```

### Update your hosts file

> your_docker_host_ip  http://chromedriver.storage.googleapis.com/

### Get xml file

> wget  http://chromedriver.storage.googleapis.com/

### Get chrome dirver file

> wget  http://chromedriver.storage.googleapis.com/2.0/chromedriver_linux64.zip





