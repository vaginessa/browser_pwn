# browser_pwn
browser pwn, main work now.

writeup will be published on [zxsq](https://t.zsxq.com/zby76AE) at first, and then on my [blog](http://ray-cp.github.io/) after a while.

* browser_pwn_basic_knowledge

    description: some basic knowledge and scripts of browser pwn.

    related link: None

    finished date: 2019

* starctf2019-oob

    description: d8 basic pwn game, with oob vuln.

    writeup: [https://t.zsxq.com/VrrfyBm](https://t.zsxq.com/VrrfyBm)

    related link: None

    finished date: 2019

* 数字经济-final-browser

    description: callback of Object::ToNumber to form uaf and oob write.

    writeup: [https://t.zsxq.com/z7MzbYn](https://t.zsxq.com/z7MzbYn)

    related link: None

    finished date: 2019

* plaidctf2018-roll_a_d8

    description: oob vuln in array.form

    writeup: [https://t.zsxq.com/iybi2JE](https://t.zsxq.com/iybi2JE)

    related link: [chromium commit](https://chromium.googlesource.com/v8/v8.git/+/b5da57a06de8791693c248b7aafc734861a3785d)

    finished date: 2019

* array_prototype_map_oob_write

    description: a oob write vuln in array.prototype.map function, with abusing use of Symbol.species

    writeup: [https://t.zsxq.com/6IufUBI](https://t.zsxq.com/6IufUBI)

    official link: [chromium commit](https://chromium.googlesource.com/v8/v8.git/+/192984ea88badc0c02e22e528b1243a9efa46f90)

    finished date: 2019

* cve-2018-17463

    description: ObjectCreate's side effect annotation

    writeup: [https://t.zsxq.com/ynUvNni](https://t.zsxq.com/ynUvNni)

    official link: [chromium commit](https://chromium.googlesource.com/v8/v8.git/+/52a9e67a477bdb67ca893c25c145ef5191976220)

    finished date: 2020.01.06

* 34c3ctf-v9

    description: exp for v9 in 34c3ctf, bug in redundancy-elimination

    writeup: [https://t.zsxq.com/jqv3JEE](https://t.zsxq.com/jqv3JEE)

    official link: [v9](https://github.com/saelo/v9)

    finished date: 2020.01.12

* 35c3ctf-krautflare

    description: exp for krautflare in 34c3ctf, bug in type optimization

    writeup: [https://t.zsxq.com/3ZRFEIi](https://t.zsxq.com/3ZRFEIi)

    official link: [Issue 1710: Chrome: V8: incorrect type information on Math.expm1](https://bugs.chromium.org/p/project-zero/issues/detail?id=1710)

    finished date: 2020.01.25

* google-ctf2018-final-just-in-time

    description: exp for just in time game in google ctf 2018 final, bug in type optimization, with the characteristic of Number.MAX_SAFE_INTEGER.

    writeup: [https://t.zsxq.com/JMnUFyV](https://t.zsxq.com/JMnUFyV)

    official link: [pwn-just-in-time](https://github.com/google/google-ctf/tree/master/2018/finals/pwn-just-in-time)

    finished date: 2020.02.04

* qwb2019-final-groupupjs

    description: exp for qwb 2019 final groupupjs, oob bug in kUint32LessThan.

    writeup: [https://t.zsxq.com/3jaaieI](https://t.zsxq.com/3jaaieI)

    official link: None

    finished date: 2020.02.08

* cve-2016-5168

    description: invalidate stable map assumption for globals on creankshaft, exploit with `null String` object

    writeup: [https://t.zsxq.com/bey3NjI](https://t.zsxq.com/bey3NjI)

    official link: [Fix](https://chromium.googlesource.com/v8/v8/+/2bd7464ec1efc9eb24a38f7400119a5f2257f6e6)

    finished date: 2020.02.18

* cve-2017-5070

    description: invalid side effection judge for global value.

    writeup: None

    official link: [issue](https://bugs.chromium.org/p/chromium/issues/detail?id=722756)

    finished date: 2020.02.24

* cve-2020-6418

    description: JSCreate can have side effects, bug in receiver maps inference.

    writeup: [browser-pwn cve-2020-6418漏洞分析](https://ray-cp.github.io/archivers/browser-pwn-cve-2020-6418%E6%BC%8F%E6%B4%9E%E5%88%86%E6%9E%90)

    official link: [commit](https://chromium.googlesource.com/v8/v8/+/fb0a60e15695466621cf65932f9152935d859447)

    finished date: 2020.02.28
