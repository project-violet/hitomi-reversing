# Hitomi Reverse

## gg.js

```
http://ltn.hitomi.la/gg.js의 정의 파일
```

```js
 var r = '';
 for (var i = 0; i < 4096; i++) {
   // console.log(gg.m[i] + ',');
   r += gg.m(i).toString();
   r += ",";
 }
 console.log(r);
```

gg.js의 gg.m함수는 4096이상의 수를 0을 리턴하며, 그 미만의 수의 대해선
미리 정의된 0또는 1의 숫자로 반환된다.

## 2096977.js

```json
[ 'https://ba.hitomi.la/webp/1639745412/3140/d59a76d1da6f55c31c1cb1d496f86ac1a4dbe0e44b7d6b9346256da8ca56c44c.webp',
  'https://aa.hitomi.la/webp/1639745412/1817/1420ab0856575a39e35f3579c128fa4435a655fefefb073ec01fc89093fd7197.webp',
  'https://ba.hitomi.la/webp/1639745412/3866/363fa24e2c53753f09e2d38a92c0d8d4d857ff3bdb716564a90058da0b7a31af.webp',
  'https://ba.hitomi.la/webp/1639745412/1427/d0680836ab0abb055a7005af764ac7bbba41d105029de244ca31f8d8f252e935.webp',
  'https://aa.hitomi.la/webp/1639745412/623/4279f505498bb677120af50b1483c319c94e7a58e3933bebd76fd6d233fd26f2.webp',
  'https://aa.hitomi.la/webp/1639745412/1442/0e6ca3e9fadd25c50b30a88c8de4c83bbb085aa109466095aab1801797592a25.webp',
  'https://ba.hitomi.la/webp/1639745412/1009/da502008149d13612246eafccbcab202e8dfab8e3faefb0b63a9cc2132405f13.webp',
  'https://ba.hitomi.la/webp/1639745412/1341/d1eb46cb87f2de446dc6c043018a7c0bfaf8e743f02cbb50f0ef7cb23a5693d5.webp',
  'https://ba.hitomi.la/webp/1639745412/2981/9e64c2f7465f6eeeb5232797df395705273daceffbe0869ba0652c445f038a5b.webp',
  'https://aa.hitomi.la/webp/1639745412/2158/d2dcf77e6566b05dd76c21e0afe1bb87ce4609a79fa0cf2261ccab3e052ae6e8.webp',
  'https://aa.hitomi.la/webp/1639745412/1016/e8793a5c6ac75aebfc6ec6037089a2ae720e78d044148712058cac1bfa2e8f83.webp',
  'https://ba.hitomi.la/webp/1639745412/3800/655a675d09090d675cc12e8d9fe0acaec0e85a1bd55efaca5ad9164939db7d8e.webp',
  'https://ba.hitomi.la/webp/1639745412/2283/122349470951f78bc92f3b3be5718163c1ce04fdb3275e1e021316c3f4a49eb8.webp' ]
```

```
curl https://ba.hitomi.la/webp/1639745412/3140/d59a76d1da6f55c31c1cb1d496f86ac1a4dbe0e44b7d6b9346256da8ca56c44c.webp -e https://hitomi.la -o 001.webp
```