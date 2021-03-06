**This wiki tracks known implementations of HTTP/2. See also our [Tools listing](Tools).**

Please add your implementation below. 

name | language | version | role(s) | negotiation(s) | protocol id(s) | refer |
--- | --- | --- | --- | --- | --- | ---
[Ace](https://github.com/CrowdHailer/Ace) | Elixir | | client, server | ALPN | h2
[Aerys](https://github.com/amphp/aerys) | PHP | | server | ALPN, Upgrade, direct | h2, h2c
[Akamai GHost](AkamaiGHost) | C++ | | intermediary | ALPN, NPN | h2, h2-14
[Apache HTTP Server 2.4.17+](http://httpd.apache.org/) | C | | server | ALPN, Upgrade, direct | h2, h2c
[Apache HttpComponents 5.0-beta1](https://hc.apache.org/) | Java | | client,server | ALPN, Upgrade, direct | h2
[Apache Traffic Server v5.3.0](http://trafficserver.apache.org/) | C++ | | intermediary | ALPN, NPN | h2, h2-14
[Apache Tomcat 8.5+](http://tomcat.apache.org/) | Java | | Server | ALPN, Upgrade, direct | h2, h2c
[Armeria](https://line.github.io/armeria/) | Java | | client, server | ALPN, Upgrade, direct | h2, h2c
[http4s-blaze](https://github.com/http4s/blaze) | Scala | | server | ALPN | h2, h2-14
[Brocade Traffic Manager (formerly Riverbed/Zeus TM)](http://www.brocade.com/products/all/application-delivery-controllers/product-details/steelapp-traffic-manager/index.page) | C++ | | Server | ALPN, Upgrade, direct | h2, h2c
[Chatterbox](https://github.com/joedevivo/chatterbox) | Erlang | | Server, Client | ALPN | h2
[Chromium](https://sites.google.com/a/chromium.org/dev/spdy/http2) | C++ | | client | ALPN | h2, h2-14
[Chicken Scheme hpack lib](http://wiki.call-cc.org/eggref/4/hpack) | Chicken Scheme | | hpack | direct | h2-14
[cl-http2-protocol](https://github.com/akamai/cl-http2-protocol) | Common Lisp | | client, server | NPN, direct | h2-14
[curl and libcurl](http://curl.haxx.se/) | C | | client | ALPN, NPN, Upgrade, Direct | h2-14, h2c-14
[Cutelyst](https://cutelyst.org) | C++ | 2.0+ | Server | ALPN, NPN, Upgrade, Direct | h2, h2c
[Dart](https://github.com/dart-lang/http2) | Dart | | client, server | ALPN, direct | h2
[Deuterium](http://robbysimpson.com/deuterium) | C | | client, server | ALPN, direct | h2, h2-14, h2c, h2c-14
[E2 Systems PATH](http://www.e2-systems.co.uk) | C | | Client, Proxy, Server (Testing tool) | ALPN | h2
[elixir-hpack](https://github.com/nesQuick/elixir-hpack) | Elixir | | HPACK |  | 
[Ericsson MSP](EricssonMSP) | | | proxy | NPN, Upgrade, direct |  h2, h2-14, h2c, h2c-14
[F5](F5)| C | | server, proxy | ALPN, NPN | h2 (from BIG-IPv12.0.0 onwards)
[GFE](gfe) | C++ | | intermediary | ALPN, NPN | h2
[HAProxy](http://www.haproxy.org/) | C | 1.8+ | intermediary | ALPN, NPN | h2 |
[h2](https://github.com/carllerche/h2) | Rust | | client, server | | h2, h2c
[H2O](https://github.com/h2o/h2o) | C | | Server, proxy | ALPN, NPN, Upgrade, direct | h2, h2-14, h2-16 |
[HH](https://github.com/64/hh) | C | | Server | ALPN | h2 |
[Haskell http2 lib](http://hackage.haskell.org/package/http2) | Haskell | | HPACK, framing | |
[hpack](https://github.com/joedevivo/hpack) | Erlang | | HPACK |  | 
[hpack](https://github.com/kylef/hpack.swift) | Swift | | HPACK |  | 
[http-2](https://github.com/igrigorik/http-2) | Ruby | | server, client | ALPN, NPN, Upgrade, direct | h2, h2c, h2-17
[http2](https://golang.org/x/net/http2) | Go | | client, server | NPN, ALPN    | h2, h2-14
[http2](https://github.com/nekolunar/http2) | Go | | server, client | ALPN, Upgrade | h2, h2c
[http2-client](https://github.com/lucasdicioccio/http2-client) | Haskell | | client | ALPN, direct | h2
[http2dotnet](https://github.com/Matthias247/http2dotnet) | C# | | server, client | ALPN & NPN (external), Upgrade, direct | h2, h2c
[HttpTwo](https://github.com/Redth/HttpTwo) | C# | | client |  direct  | h2, h2c
[httpbis](https://github.com/stepancheg/rust-http2) | Rust | | client, server | | 
[hyper](http://python-hyper.org) | Python | | client, server | NPN, ALPN | h2, h2c
[Shaka Technologies Ishlangu Load Balancer](https://www.shakatechnologies.com/) | C, Java | | server, proxy | ALPN | h2
[Jetty](https://github.com/eclipse/jetty.project) | Java | | client, intermediary, server | ALPN, Upgrade, Direct | h2, h2-17, h2-14, h2c, h2c-17
[libcno](https://github.com/pyos/libcno) | C / Python wrapper | | Server, Client, HPACK | ALPN, Upgrade, direct | h2, h2c
[LiteSpeed Enterprise](http://www.litespeedtech.com) | C++ | | Server | ALPN, NPN, Upgrade | h2, h2-17, h2-14, h2c
[ls-hpack](https://github.com/litespeedtech/ls-hpack) | C | | HPACK | | |
[lua-http](https://github.com/daurnimator/lua-http/) | Lua | | client, server | ALPN, direct | h2
[Lucid](https://github.com/tatsuhiro-t/lucid) | Erlang | | Server | NPN, direct | h2, h2-16, h2-14
[Microsoft](https://github.com/http2/http2-spec/wiki/Microsoft-HTTP-2-Prototype) | C/C++ | | Client, Server | ALPN | h2
[Microsoft Internet Explorer](http://windows.microsoft.com/en-us/internet-explorer/download-ie) | | | client | ALPN (others?) | h2 (Windows 10 only?)
[mod_h2](https://icing.github.io/mod_h2/) | C | | Server | ALPN, Upgrade, direct | h2, h2c
[Mozilla Firefox](https://wiki.mozilla.org/Networking/http2) | C++ | 49 | client | ALPN, NPN | h2-15, h2-14, h2 | http://caniuse.com/#search=http2
[Netty](http://netty.io/) | Java | | client, server | ALPN, NPN, Upgrade, direct | h2, h2c
[Nimble Streamer](https://wmspanel.com/nimble) | C++ | 3.6.2-1 | server | ALPN | h2 | [Live HLS and MPEG-DASH only](https://blog.wmspanel.com/2019/11/http2-in-nimble-streamer.html)
[nghttp2](https://nghttp2.org) | C | | client, server, intermediary | ALPN, NPN, Upgrade, direct | h2, h2-16, h2-14, h2c
[Radware](https://www.radware.com/FastViewHTTP2/) | C++/C | | proxy, server | ALPN | h2
[NGINX](https://www.nginx.com/blog/nginx-1-9-5/) | C | 1.9.5+ | server | ALPN, NPN, direct | h2, h2c | [Open Source NGINX 1.9.5 Released with HTTP/2 Support](https://www.nginx.com/blog/nginx-1-9-5/)
[Node.js](https://nodejs.org/api/http2.html) | Node.js | 8.4.0+ | server, client | ALPN, NPN, direct | h2, h2c
[node-http2](https://github.com/molnarg/node-http2) | Node.js | | server, client | ALPN, NPN, direct | h2
[node-spdy](https://github.com/indutny/node-spdy) | Node.js | | server, client | ALPN, NPN, direct | h2
[nuster](https://github.com/jiangwenyuan/nuster) | C | 1.8+ | intermediary | ALPN, NPN | h2 |
[OkHttp](https://github.com/square/okhttp) | Android, Java | | mock server, client | ALPN, NPN | h2
[ocaml-h2](https://github.com/anmonteiro/ocaml-h2) | OCaml | | server, client | ALPN, Upgrade, direct    | h2, h2c
[Fast Android Networking](https://github.com/amitshekhariitbhu/Fast-Android-Networking) | Android, Java | | client | ALPN, NPN | h2
[OpenLiteSpeed](http://open.litespeedtech.com) | C++ | | Server | ALPN, NPN, Upgrade | h2, h2-17 , h2-14, h2c
[Protocol::HTTP2](https://github.com/vlet/p5-Protocol-HTTP2) | Perl | | server, client | ALPN, NPN, Upgrade, direct | h2, h2c
[River](https://github.com/peburrows/river) | Elixir | | client | ALPN | h2
[Sasazka](https://github.com/summerwind/sasazka) | Node.js | | server | NPN |
[second-transfer](https://github.com/alcidesv/second-transfer) | Haskell | | server | ALPN | h2-14, h2
[ShimmerCat](https://www.shimmercat.com) | Haskell | | server | ALPN, Ahead Of Time Transfer Engine | h2 
[SuaveIO](https://github.com/SuaveIO/suave) | F# | | server | | h2 (not yet ready, pull req: https://github.com/SuaveIO/suave/pull/434)
[Swoole](https://github.com/swoole/swoole-src) | PHP | | server | ALPN, NPN | h2 
[Trusterd](https://github.com/matsumoto-r/trusterd) | C/mruby | | client, server | ALPN, NPN, direct | h2, h2c
[Twisted](https://twistedmatrix.com) | Python | | server | NPN, ALPN | h2
[Twitter](https://twitter.com/) | C++ | | server, client | ALPN, NPN | h2
[Undertow](https://http2.undertow.io) | Java | | Server, Intermediary | ALPN, Upgrade |
[Vert.x](http://vertx.io/) | Java | | Client, Server | ALPN, Upgrade, direct | h2, h2c
[WASD](http://wasd.vsm.com.au/) | C/OpenVMS | | Server | ALPN, Upgrade, direct | h2, h2c
[Warp](http://hackage.haskell.org/package/warp) | Haskell | | Server | ALPN, direct |
[Wget2 and libwget](https://gitlab.com/gnuwget/wget2) | C | | Client | ALPN? | ? (libnghttp2) 
[Wireshark](https://bugs.wireshark.org/bugzilla/show_bug.cgi?id=9042) | C | | other | ALPN, NPN, Upgrade, direct |
[WKWebView](https://developer.apple.com/library/ios/documentation/WebKit/Reference/WKWebView_Ref/) | Obj-C, Swift | | client | |
[cashpack](https://github.com/Dridi/cashpack) | C | | HPACK | |
[proxygen](https://github.com/facebook/proxygen) | C++ | | Server, Client | ALPN, NPN, Upgrade| h2
[firefly](https://github.com/hypercube1024/firefly) | Java | | Server, Client | ALPN, Upgrade | h2, h2c
[heaphttpd](https://github.com/uplusware/heaphttpd) | C++ | | Server | ALPN, Upgrade | h2, h2c
[HTTP-2-server](https://github.com/kape142/HTTP-2-server) | C# | 0.1.0| Server | ALPN, Upgrade | h2, h2c
[http2_client](https://github.com/jamesnvc/http2_client) | Prolog |  | Client | ALPN | h2
[Tempesta FW](https://github.com/tempesta-tech/tempesta) | C | 0.7.0 | Proxy | ALPN | h2

## Older Implementations

name | version | language | role(s) | negotiation(s) | protocol id(s) | refer
--- | --- | --- | --- | --- | --- | ---
[http2-katana](https://github.com/MSOpenTech/http2-katana) | C#/C | | server, test client | ALPN, Upgrade | h2-12
[http2-perl](https://github.com/sludin/http2-perl) | Perl | | client, server | NPN | h2-04
[iij-http2](https://github.com/shigeki/interop-iij-http2) | NodeJS | | client, server| ALPN, NPN | h2-13
[http2-go](https://github.com/Jxck/http2) | Go | | client, server | NPN | h2-12

## - PHP Based

  Using Apache wouldn't be practical as it's using a nuclear bomb when a firecracker will suffice. Creating a PHP server is quite simple on Linux with the help of xinetd.

  Modify /etc/services. Say you want your service to run on port 56789. In /etc/services, add the line:

  gpsservice   56789/tcp

  In /etc/xinet.d/, create a file named gpsservice:

  service gpsservice 
  {
      socket_type             = stream
      protocol                = tcp
      wait                    = no
      user                    = yourusername
      server                  = /path/to/your/script
      log_on_success          = HOST PID
      disable                 = no
  }

  Create your PHP script (chmod it to be executable):

  #!/usr/bin/php
  <?php
  // do stuff
  ?>

  Restart xinetd service xinetd restart

  You now have a quick TCP server written in PHP.




###  Ref
  * https://http2.github.io/faq/#is-it-http20-or-http2
  * https://icing.github.io/mod_h2/howto.html#nghttp
