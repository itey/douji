# Bitcoinproof

![](48435a4aaa6e9708f6b23b8e0833568.png)



为比特币网络保护的数据创建防伪时间戳。

一、防伪

身份认证：

我们知道传统的认证方式有：人脸识别，签名，指纹验证。但是这三种方式在比特币交易上都不能实现，因为通过计算机可以将上述几种方式拷贝下来，然后添加到伪造记录上。

于是就衍生出了一种新的方式：电子签名。所谓电子签名，就是比特币用户在注册的时候，系统会产生一个随机数。通过这个随机数产生私钥字符串，然后再通过私钥再产生公钥字符串，私钥和公钥是对应的，最后产生出地址。

私钥顾名思义是你的私人钥匙，必须自己保密好，如果你的钥匙弄丢了，那么你的比特币也就会不见了。所以最安全的方式就是把他背下来记在自己的脑子里。

公钥和地址都是公开的

如果你想让别人给你钱的话，你只需要把地址告诉他。如果你想给别人钱的话就把自己的公钥和地址都告诉他。

私钥和公钥的作用

私钥通过对一串字符进行加密，而公钥则负责对一串字符进行解密。私钥和公钥的加密方式为非对称加密，即只有你可以加密，而任何人都可以解密。

然后，利用上述私钥公钥通过哈希运算来进行加密防伪

二、防止篡改

比特币有个最长链原则。比如，已经有五个块组成了一个链，此时，有两个人同时挖出了两个新的块。那么从此刻起，往后只要有人通过这两个块之中的某一个最先挖出一个新块，那么这两个新块就可以连接到之前的五个块上组成的链上。与此同时，另一个人的挖出的块也就没用了，当然，如果你认为你以此块可以更快的挖出第二个第三个个块，能够更快的成为更长链，你也可以继续下去，只不过这样就是有点势单力薄。

假如甲想要抹掉自己给乙10个比特币的记录。那么你就需要以一己之力去对抗更多的人，然后去更快的挖出更多的块。理论上来说，是可以的。但是这基本上等于自己一个人与世界上全世界的人做对。所以说比特币的防伪属性还是比较好的。


