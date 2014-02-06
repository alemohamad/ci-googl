# CodeIgniter Library: goo.gl

**ci-googl**

## About this library

This CodeIgniter's Library that shrotens and extends URLs with goo.gl service.  

I recommend you to save the shorten URL in a DB or a cache, because of the limit usage of the service.  

Its usage is recommended for CodeIgniter 2 or greater.  

## Usage

```php
$this->load->library('Googl');

$this->googl->shorten('http://www.github.com/');

$this->googl->expand('http://goo.gl/CyLE');
```

![Ale Mohamad](http://alemohamad.com/github/logo2012am.png)
