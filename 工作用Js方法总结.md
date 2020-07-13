主要整理日常工作中常用的一些通用Js代码，以方便能够记录与使用。

- [1.截取指定字节数的字符串](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#1%E6%88%AA%E5%8F%96%E6%8C%87%E5%AE%9A%E5%AD%97%E8%8A%82%E6%95%B0%E7%9A%84%E5%AD%97%E7%AC%A6%E4%B8%B2)
- [2.判断是否微信](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#2%E5%88%A4%E6%96%AD%E6%98%AF%E5%90%A6%E5%BE%AE%E4%BF%A1)
- [3.获取时间格式的几个举例](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#3%E8%8E%B7%E5%8F%96%E6%97%B6%E9%97%B4%E6%A0%BC%E5%BC%8F%E7%9A%84%E5%87%A0%E4%B8%AA%E4%B8%BE%E4%BE%8B)
- [4.获取字符串字节长度](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#4%E8%8E%B7%E5%8F%96%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%AD%97%E8%8A%82%E9%95%BF%E5%BA%A6)
- [5.对象克隆、深拷贝](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#5%E5%AF%B9%E8%B1%A1%E5%85%8B%E9%9A%86%E6%B7%B1%E6%8B%B7%E8%B4%9D)
- [6.组织结构代码证验证](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#6%E7%BB%84%E7%BB%87%E7%BB%93%E6%9E%84%E4%BB%A3%E7%A0%81%E8%AF%81%E9%AA%8C%E8%AF%81)
- [7.身份证号验证](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#7%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%8F%B7%E9%AA%8C%E8%AF%81)
- [8.js正则为url添加http标识](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#8js%E6%AD%A3%E5%88%99%E4%B8%BAurl%E6%B7%BB%E5%8A%A0http%E6%A0%87%E8%AF%86)
- [9.URL有效性校验方法](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#9url%E6%9C%89%E6%95%88%E6%80%A7%E6%A0%A1%E9%AA%8C%E6%96%B9%E6%B3%95)
- [10.自定义jsonp方法](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#10%E8%87%AA%E5%AE%9A%E4%B9%89jsonp%E6%96%B9%E6%B3%95)
- [11.cookie操作](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#11cookie%E6%93%8D%E4%BD%9C)
- [12.生成随机字符串(可指定长度)](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#12%E7%94%9F%E6%88%90%E9%9A%8F%E6%9C%BA%E5%AD%97%E7%AC%A6%E4%B8%B2%E5%8F%AF%E6%8C%87%E5%AE%9A%E9%95%BF%E5%BA%A6)
- [13.浏览器判断](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#13%E6%B5%8F%E8%A7%88%E5%99%A8%E5%88%A4%E6%96%AD)
- [14.Rem移动端适配](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#14rem%E7%A7%BB%E5%8A%A8%E7%AB%AF%E9%80%82%E9%85%8D)
- [15.获取url后参数](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#15%E8%8E%B7%E5%8F%96url%E5%90%8E%E5%8F%82%E6%95%B0)
- [16.动态加载JS](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#16%E5%8A%A8%E6%80%81%E5%8A%A0%E8%BD%BDjs)
- [17.生成随机颜色值](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#17%E7%94%9F%E6%88%90%E9%9A%8F%E6%9C%BA%E9%A2%9C%E8%89%B2%E5%80%B)
- [18.事件绑定与解绑](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#18%E4%BA%8B%E4%BB%B6%E7%BB%91%E5%AE%9A%E4%B8%8E%E8%A7%A3%E7%BB%91)
- [19.移动端音频播放](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#19%E7%A7%BB%E5%8A%A8%E7%AB%AF%E9%9F%B3%E9%A2%91%E6%92%AD%E6%94%BE)
- [20.移动端视频适配](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#20%E7%A7%BB%E5%8A%A8%E7%AB%AF%E8%A7%86%E9%A2%91%E9%80%82%E9%85%8D)
- [21.Webpack+Vue-CLI实现自动全局注册组件](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#21webpackvue-cli%E5%AE%9E%E7%8E%B0%E8%87%AA%E5%8A%A8%E5%85%A8%E5%B1%80%E6%B3%A8%E5%86%8C%E7%BB%84%E4%BB%B6)
- [22.精度计算](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#22%E7%B2%BE%E5%BA%A6%E8%AE%A1%E7%AE%97)
- [23.统一社会信用代码](https://github.com/lengxing/MyBlog/blob/master/%E5%B7%A5%E4%BD%9C%E7%94%A8Js%E6%96%B9%E6%B3%95%E6%80%BB%E7%BB%93.md#23%E7%BB%9F%E4%B8%80%E7%A4%BE%E4%BC%9A%E4%BF%A1%E7%94%A8%E4%BB%A3%E7%A0%81%E9%AA%8C%E8%AF%81)

### 1.截取指定字节数的字符串

```javascript
/**
 * 截取指定字节的字符串
 * @param str 要截取的字符穿
 * @param len 要截取的长度，根据字节计算
 * @param suffix 截取前len个后，其余的字符的替换字符，一般用“…”
 * @returns {*}
 */
function cutString(str,len,suffix){
   if(!str) return "";
   if(len <= 0) return "";
   if(!suffix) suffix = "";
   var templen = 0;
   for(var i = 0;i < str.length;i++){
      if(str.charCodeAt(i) > 255){
         templen += 2;
      }else{
         templen++
      }
      if(templen == len){
         return str.substring(0, i+1) + suffix;
      }else if(templen > len){
         return str.substring(0, i) + suffix;
      }
   }
   return str;
}
``` 
### 2.判断是否微信
```javascript 
/**
 * 判断微信浏览器
 * @returns {Boolean}
 */
function isWeiXin() {
    var ua = window.navigator.userAgent.toLowerCase();
    if (ua.match(/MicroMessenger/i) == 'micromessenger') {
        return true;
    } else {
        return false;
    }
}
```  
### 3.获取时间格式的几个举例
```javascript
function getTimeFormat(time){
   var date = new Date(parseInt(time) * 1000);
   var month,day,hour,min;
   parseInt(date.getMonth())+1<10?month = '0'+(parseInt(date.getMonth())+1):month = parseInt(date.getMonth())+1;
   date.getDate()<10?day = '0'+date.getDate():day = date.getDate();
   date.getHours()<10?hour = '0'+date.getHours():hour = date.getHours();
   date.getMinutes()<10?min = '0'+date.getMinutes():min = date.getMinutes();
   return [month, day].join('-')+'  '+hour+':'+min
}

function getTimeFormatYMD(time) {
    var date = new Date(parseInt(time) * 1000);
    var year, month,day;
    year = date.getFullYear();
    parseInt(date.getMonth())+1<10?month = '0'+(parseInt(date.getMonth())+1):month = parseInt(date.getMonth())+1;
    date.getDate()<10?day = '0'+date.getDate():day = date.getDate();
    return [year, month, day].join('-')
}

function getTimeFormatAll(time) {
   var date = new Date(parseInt(time) * 1000);
   var year, month,day,hour,min, second;
   year = date.getFullYear();
   parseInt(date.getMonth())+1<10?month = '0'+(parseInt(date.getMonth())+1):month = parseInt(date.getMonth())+1;
   date.getDate()<10?day = '0'+date.getDate():day = date.getDate();
   date.getHours()<10?hour = '0'+date.getHours():hour = date.getHours();
   date.getMinutes()<10?min = '0'+date.getMinutes():min = date.getMinutes();
   date.getSeconds()<10?second = '0'+date.getSeconds():second = date.getSeconds();

   return [year, month, day].join('-')+'  '+hour+':'+min+':'+second
}
```
### 4.获取字符串字节长度
```javascript
/**
 * 获取字符串字节长度
 * @param {String}
 * @returns {Boolean}
 */
function checkLength(v){         
    var realLength = 0;
    var len = v.length;
    for (var i = 0; i < len; i++) {
       var charCode = v.charCodeAt(i);
       if (charCode >= 0 && charCode <= 128)
           realLength += 1;
       else
           realLength += 2;
   }
   return realLength;
}
```  
### 5.对象克隆、深拷贝
```javascript
/**
 * 对象克隆&深拷贝
 * @param obj
 * @returns {{}}
 */
function cloneObj(obj) {
    var newO = {};

    if (obj instanceof Array) {
        newO = [];
    }
    for (var key in obj) {
        var val = obj[key];
        newO[key] = typeof val === 'object' ? arguments.callee(val) : val;
    }
    return newO;
};
```
    克隆拷贝增强版
```javascript
/**
 * 对象克隆&深拷贝
 * @param obj
 * @returns {{}}
 */
function clone(obj) {
    // Handle the 3 simple types, and null or undefined
    if (null == obj || "object" != typeof obj) return obj;

    // Handle Date
    if (obj instanceof Date) {
        var copy = new Date();
        copy.setTime(obj.getTime());
        return copy;
    }

    // Handle Array
    if (obj instanceof Array) {
        var copy = [];
        for (var i = 0, len = obj.length; i < len; ++i) {
            copy[i] = clone(obj[i]);
        }
        return copy;
    }

    // Handle Object
    if (obj instanceof Object) {
        var copy = {};
        for (attr in obj) {
            if (obj.hasOwnProperty(attr)) copy[attr] = clone(obj[attr]);
        }
        return copy;
    }

    throw new Error("Unable to copy obj! Its type isn't supported.");
}
```
    测试用例：
```javascript
var origin = {
    a: "text",
    b: null,
    c: undefined,
    e: {
        f: [1, 2]
    }
}
```
### 6.组织结构代码证验证

    验证规则：

		组织机构代码是每一个机关、社会团体、企事业单位在全国范围内唯一的、始终不变的法定代码
		标识。最新使用的组织机构代码在1997年颁布实施，由8位数字（或大写拉丁字母）本体代码和
		1位数字（或大写拉丁字母）校验码组成。本体代码采用系列（即分区段）顺序编码方法。
		校验码按下列公式计算： 
		8 
		C9 = 11 - MOD ( ∑Ci * Wi ，11) … (2) 
		i=1 
		其中：MOD —— 表示求余函数； 
		i —— 表示代码字符从左到右位置序号； 
		Ci —— 表示第i位置上的代码字符的值，采用附录A“代码字符集”所列字符； 
		C9 —— 表示校验码； 
		Wi —— 表示第i位置上的加权因子，其数值如下表： 
		i 1 2 3 4 5 6 7 8 
		Wi 3 7 9 10 5 8 4 2 
		当MOD函数值为1（即 C9 = 10）时，校验码用字母X表示。

    验证方法：
```javascript
checkOrgCodeValid: function(el){
    var txtval = el.value;
    var values=txtval.split("-");
    var ws = [3, 7, 9, 10, 5, 8, 4, 2];
    var str = '0123456789ABCDEFGHIJKLMNOPQRSTUVWXYZ';
    var reg = /^([0-9A-Z]){8}$/;
    if (!reg.test(values[0])) {
        return false
    }
    var sum = 0;
    for (var i = 0; i < 8; i++) {
        sum += str.indexOf(values[0].charAt(i)) * ws[i];
    }
    var C9 = 11 - (sum % 11);
    var YC9 = values[1]+'';
    if (C9 == 11) {
        C9 = '0';
    } else if (C9 == 10) {
        C9 = 'X'  ;
    } else {
        C9 = C9+'';
    }
    return YC9 == C9;
}
```  
### 7.身份证号验证
```javascript
/**
 * 验证身份证号
 * @param el 号码输入input
 * @returns {boolean}
 */
function checkCardNo(el){
    var txtval = el.value;
    var reg = /(^\d{15}$)|(^\d{18}$)|(^\d{17}(\d|X|x)$)/;
    return reg.test(txtval)
}
```
### 8.js正则为url添加http标识
```javascript
<!DOCTYPE html>
<html lang="en" xmlns="http://www.w3.org/1999/xhtml">

<head>
    <meta charset="utf-8" />
    <title></title>
    <script>
        var html = 'http://www.google.com';
        html += '\rwww.google.com';
        html += '\rcode.google.com';
        html += '\rhttp://code.google.com/hosting/search?q=label%3aPython';
        var regex = /(https?:\/\/)?(\w+\.?)+(\/[a-zA-Z0-9\?%=_\-\+\/]+)?/gi;
        alert('before replace:');
        alert(html);
        html = html.replace(regex, function(match, capture) {
            if (capture) {
                return match
            } else {
                return 'http://' + match;
            }
        });
        alert('after replace:');
        alert(html);
    </script>
</head>

<body>
</body>

</html>
```   
### 9.URL有效性校验方法
```javascript
/**
 * URL有效性校验
 * @param str_url
 * @returns {boolean}
 */
function isURL(str_url) {// 验证url
    var strRegex = "^((https|http|ftp|rtsp|mms)?://)"
        + "?(([0-9a-z_!~*'().&=+$%-]+: )?[0-9a-z_!~*'().&=+$%-]+@)?" //           
    ftp的user@
          + "(([0-9]{1,3}\.){3}[0-9]{1,3}" // IP形式的URL- 199.194.52.184
            + "|" // 允许IP和DOMAIN（域名）
            + "([0-9a-z_!~*'()-]+\.)*" // 域名- www.
            + "([0-9a-z][0-9a-z-]{0,61})?[0-9a-z]\." // 二级域名
            + "[a-z]{2,6})" // first level domain- .com or .museum
            + "(:[0-9]{1,4})?" // 端口- :80
            + "((/?)|" // a slash isn't required if there is no file name
            + "(/[0-9a-z_!~*'().;?:@&=+$,%#-]+)+/?)$";
    var re = new RegExp(strRegex);
    return re.test(str_url);
}

// 建议的正则
  functionisURL(str){
      return!!str.match(/(((^https?:(?:\/\/)?)(?:[-;:&=\+\$,\w]+@)?[A-Za-z0-9.-]+|(?:www.|[-;:&=\+\$,\w]+@)[A-Za-z0-9.-]+)((?:\/[\+~%\/.\w-_]*)?\??(?:[-\+=&;%@.\w_]*)#?(?:[\w]*))?)$/g);
  }
```  
### 10.自定义jsonp方法
```javascript
/**
 * 自定义封装jsonp方法
 * @param options
 */
jsonp = function(options) {
    options = options || {};
    if (!options.url || !options.callback) {
        throw new Error("参数不合法");
    }

    //创建 script 标签并加入到页面中
    var callbackName = ('jsonp_' + Math.random()).replace(".", "");
    var oHead = document.getElementsByTagName('head')[0];
    options.data[options.callback] = callbackName;
    var params = formatParams(options.data);
    var oS = document.createElement('script');
    oHead.appendChild(oS);

    //创建jsonp回调函数
    window[callbackName] = function (json) {
        oHead.removeChild(oS);
        clearTimeout(oS.timer);
        window[callbackName] = null;
        options.success && options.success(json);
    };

    //发送请求
    oS.src = options.url + '?' + params;

    //超时处理
    if (options.time) {
        oS.timer = setTimeout(function () {
            window[callbackName] = null;
            oHead.removeChild(oS);
            options.fail && options.fail({ message: "超时" });
        }, time);
    }
};
/**
 * 格式化参数
 * @param data
 * @returns {string}
 */
formatParams = function(data) {
    var arr = [];
    for (var name in data) {
        arr.push(encodeURIComponent(name) + '=' + encodeURIComponent(data[name]));
    }
    return arr.join('&');
}
```  
### 11.cookie操作
```javascript
//写cookies
setCookie = function(name,value,time) {
    var strsec = getsec(time);
    var exp = new Date();
    exp.setTime(exp.getTime() + strsec*1);
    document.cookie = name + "="+ escape (value) + ";expires=" + exp.toGMTString();
}
//cookie操作辅助函数
getsec = function(str){
    var str1=str.substring(1,str.length)*1;
    var str2=str.substring(0,1);
    if (str2=="s"){
        return str1*1000;
    }else if (str2=="h"){
        return str1*60*60*1000;
    }else if (str2=="d"){
        return str1*24*60*60*1000;
    }
}
//读取cookies
getCookie = function(name) {
    var arr,reg=new RegExp("(^| )"+name+"=([^;]*)(;|$)");
    if(arr=document.cookie.match(reg))
        return (arr[2]);
    else
        return null;
}

//删除cookies
delCookie = function(name) {
    var exp = new Date();
    exp.setTime(exp.getTime() - 1);
    var cval = getCookie(name);
    if(cval != null)
        document.cookie= name + "="+cval+";expires="+exp.toGMTString();
}
```  
### 12.生成随机字符串(可指定长度)
```javascript
/**
 * 生成随机字符串(可指定长度)
 * @param len
 * @returns {string}
 */
randomString = function(len) {
    len = len || 8;
    var $chars = 'ABCDEFGHJKMNPQRSTWXYZabcdefhijkmnprstwxyz2345678';    /****默认去掉了容易混淆的字符oOLl,9gq,Vv,Uu,I1****/
    var maxPos = $chars.length;
    var pwd = '';
    for (var i = 0; i < len; i++) {
        pwd += $chars.charAt(Math.floor(Math.random() * maxPos));
    }
    return pwd;
}
```  

### 13.浏览器判断

```javascript
function parseUA() {
    var u = navigator.userAgent;
    var u2 = navigator.userAgent.toLowerCase();
    return { //移动终端浏览器版本信息
        trident: u.indexOf('Trident') > -1, //IE内核
        presto: u.indexOf('Presto') > -1, //opera内核
        webKit: u.indexOf('AppleWebKit') > -1, //苹果、谷歌内核
        gecko: u.indexOf('Gecko') > -1 && u.indexOf('KHTML') == -1, //火狐内核
        mobile: !!u.match(/AppleWebKit.*Mobile.*/), //是否为移动终端
        ios: !!u.match(/\(i[^;]+;( U;)? CPU.+Mac OS X/), //ios终端
        android: u.indexOf('Android') > -1 || u.indexOf('Linux') > -1, //android终端或uc浏览器
        iPhone: u.indexOf('iPhone') > -1, //是否为iPhone或者QQHD浏览器
        iPad: u.indexOf('iPad') > -1, //是否iPad
        webApp: u.indexOf('Safari') == -1, //是否web应该程序，没有头部与底部
        iosv: u.substr(u.indexOf('iPhone OS') + 9, 3),
        weixin: u2.match(/MicroMessenger/i) == "micromessenger",
        ali: u.indexOf('AliApp') > -1,
    };
}
var ua = parseUA();

if (!ua.mobile) {
    location.href = './pc.html';
}

```


### 14.Rem移动端适配
```javascript
var rem = {
	baseRem: 40, // 基准字号，按照iphone6应该为20，此处扩大2倍，便于计算
	baseWidth: 750, // 基准尺寸宽，此处是按照ihpone6的尺寸
	rootEle: document.getElementsByTagName("html")[0],
	initHandle: function () {
		this.setRemHandle();
		this.resizeHandle();
	},
	setRemHandle: function () {
		var clientWidth = document.documentElement.clientWidth || document.body.clientWidth;
		this.rootEle.style.fontSize = clientWidth * this.baseRem / this.baseWidth + "px";
	},
	resizeHandle: function () {
		var that = this;
		window.addEventListener("resize", function () {
			setTimeout(function () {
				that.setRemHandle();
			}, 300);
		});
	}
};
rem.initHandle();
```

### 15.获取url后参数

```javascript
function GetRequest() {            
    var url = location.search; //获取url中"?"符后的字串
    var theRequest = new Object();
    if(url.indexOf("?") != -1) {
            var str = url.substr(1);
            strs = str.split("&");
            for(var i = 0; i < strs.length; i++) {
                    theRequest[strs[i].split("=")[0]] = (strs[i].split("=")[1]);
            }
    }
    return theRequest;
}
```

### 16.动态加载JS

```javascript
function loadScript(url, callback) {
  var script = document.createElement("script");
  script.type = "text/javascript";
  if(typeof(callback) != "undefined"){
    if (script.readyState) {
      script.onreadystatechange = function () {
        if (script.readyState == "loaded" || script.readyState == "complete") {
          script.onreadystatechange = null;
          callback();
        }
      };
    } else {
      script.onload = function () {
        callback();
      };
    }
  }
  script.src = url;
  document.body.appendChild(script);
}
```

### 17.生成随机颜色值

```javascript
function getRandomColor () {
  const rgb = []
  for (let i = 0 ; i < 3; ++i){
    let color = Math.floor(Math.random() * 256).toString(16);
    color = color.length == 1 ? '0' + color : color;
    rgb.push(color);
  }
  return '#' + rgb.join('');
}
```

### 18.事件绑定与解绑

```javascript
ElementClass.prototype.on = function (name, callback) {
    this.callbacks[name] = this.callbacks[name] || []
    this.callbacks[name].push(callback)
}

ElementClass.prototype.off = function (name, callback) {
    var callbacks = this.callbacks[name]
    if (callbacks && callbacks instanceof Array) {
        var index = callbacks.indexOf(callback)
        if (index !== -1) callbacks.splice(index, 1)
    }
}

ElementClass.prototype.trigger = function (name, params) {
    var callbacks = this.callbacks[name]
    if (callbacks && callbacks instanceof Array) {
        callbacks.forEach((cb) => {
            cb(params)
        })
    }
}
```

### 19.移动端音频播放

```javascript
/**
  * 移动端H5播放音乐处理，兼容微信端
  * @param el 音乐Audio元素
  */
function playMusic(el) {
    var b = document.getElementById(el);

    var c = function c() {
        b.play();
        document.removeEventListener("touchstart", c, true);
    };

    b.play();
    document.addEventListener("WeixinJSBridgeReady", function () {
        c();
    }, false);
    document.addEventListener("YixinJSBridgeReady", function () {
        c();
    }, false);
    document.addEventListener("touchstart", c, true);
}
```

### 20.移动端视频适配

```html
<video class="video1" webkit-playsinline="true" x-webkit-airplay="true" playsinline="true" x5-video-player-type="h5" x5-video-player-fullscreen="true"  preload="auto" poster="poster图片地址" src="视频地址"></video>
```

### 21.Webpack+Vue-CLI实现自动全局注册组件

```javascript
// 需要 npm import --save lodash
import upperFirst from 'lodash/upperFirst'
import camelCase from 'lodash/camelCase'

const requireComponent = require.context(
  // 其组件目录的相对路径
  './components',
  // 是否查询其子目录
  false,
  // 匹配基础组件文件名的正则表达式，获取.vue结尾的文件
  /.vue$/
)


requireComponent.keys().forEach(fileName => {
  // 获取组件配置
  const componentConfig = requireComponent(fileName)

  // 获取组件的 PascalCase 命名
  const componentName = upperFirst(
    camelCase(
      // 剥去文件名开头的 `./` 和结尾的扩展名
      fileName.replace(/^\.\/(.*)\.\w+$/, '$1')
    )
  )

  // 全局注册组件
  Vue.component(
    componentName,
    // 如果这个组件选项是通过 `export default` 导出的，
    // 那么就会优先使用 `.default`，
    // 否则回退到使用模块的根。
    componentConfig.default || componentConfig
  )
```

### 22.精度计算

```javascript
/**
* 加法运算，避免数据相加小数点后产生多位数和计算精度损失。
*
* @param num1加数1 | num2加数2
*/
function numAdd (num1, num2) {
    var baseNum, baseNum1, baseNum2;
    try {
        baseNum1 = num1.toString().split('.')[1].length;
    } catch (e) {
        baseNum1 = 0;
    }
    try {
        baseNum2 = num2.toString().split('.')[1].length;
    } catch (e) {
        baseNum2 = 0;
    }
    baseNum = Math.pow(10, Math.max(baseNum1, baseNum2));
    return (num1 * baseNum + num2 * baseNum) / baseNum;
}

/**
* 加法运算，避免数据相减小数点后产生多位数和计算精度损失。
*
* @param num1被减数 | num2减数
*/
function numSub (num1, num2) {
    var baseNum, baseNum1, baseNum2;
    var precision; // 精度
    try {
        baseNum1 = num1.toString().split('.')[1].length;
    } catch (e) {
        baseNum1 = 0;
    }
    try {
        baseNum2 = num2.toString().split('.')[1].length;
    } catch (e) {
        baseNum2 = 0;
    }
    baseNum = Math.pow(10, Math.max(baseNum1, baseNum2));
    precision = (baseNum1 >= baseNum2) ? baseNum1 : baseNum2;
    return ((num1 * baseNum - num2 * baseNum) / baseNum).toFixed(precision);
}

/**
* 乘法运算，避免数据相乘小数点后产生多位数和计算精度损失。
*
* @param num1被乘数 | num2乘数
*/
function numMulti (num1, num2) {
    var baseNum = 0;
    try {
        baseNum += num1.toString().split('.')[1].length;
    } catch (e) {
        console.error('numMulti error')
    }
    try {
        baseNum += num2.toString().split('.')[1].length;
    } catch (e) {
        console.error('numMulti error')
    }
    return Number(num1.toString().replace('.', '')) * Number(num2.toString().replace('.', '')) / Math.pow(10, baseNum);
}

/**
* 除法运算，避免数据相除小数点后产生多位数和计算精度损失。
*
* @param num1被除数 | num2除数
*/
function numDiv (num1, num2) {
    var baseNum1 = 0,
        baseNum2 = 0;
    var baseNum3, baseNum4;
    try {
        baseNum1 = num1.toString().split('.')[1].length;
    } catch (e) {
        baseNum1 = 0;
    }
    try {
        baseNum2 = num2.toString().split('.')[1].length;
    } catch (e) {
        baseNum2 = 0;
    }
    baseNum3 = Number(num1.toString().replace('.', ''));
    baseNum4 = Number(num2.toString().replace('.', ''));
    return (baseNum3 / baseNum4) * Math.pow(10, baseNum2 - baseNum1);
}
```

### 23.统一社会信用代码验证

规则：

![统一社会信用代码规则](https://github.com/lengxing/MyBlog/blob/master/Images/socialCode.png)

```javascript
/**
* @description 验证统一社会信用代码
* @param socialCode 被验证代码
* @return Boolean
*/
function isSocialCode(socialCode) {
  const reg = /[0-9A-HJ-NPQRTUWXY]{2}\d{6}[0-9A-HJ-NPQRTUWXY]{10}/;
  return reg.test(socialCode);
}

```
