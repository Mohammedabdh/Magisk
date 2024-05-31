<!doctype html><html lang="ar">

<head>

<meta charset="UTF-8"><title data-network-name>شبكة{{network-name}} اللاسلكيه</title>

<meta name="viewport" content="width=device-width,initial-scale=1">

<meta name="theme-color" content="#8277d1">

<link rel="shortcut icon" type="image/x-icon" href="img/favicon.ico">

<meta http-equiv="pragma" content="no-cache"><meta http-equiv="expires" content="-1">

<link rel="stylesheet" href="css/sweetalert2.min.css">

<link rel="stylesheet" href="css/fontello.min.css">

<link rel="stylesheet" href="css/style.min.css">

<link rel="stylesheet" href="css/osama.css">

<link rel="stylesheet" href="css/speed.css"><script charset="UTF-8" src="js/sweetalert2.all.min.js"></script><form name="sendin" action=" style="display:none"><input type="hidden" name="username" /><input type="hidden" name="password" value="" /><input type="hidden" name="dst" value="" /><input type="hidden" name="var" value="chap" /></form>

<script>var jsonData = {};var ChapChar={};</script>

<script>jsonData = {"idle_timeout": "", "refresh_timeout": "", "uptime": "0s", "session_timeout": "00", "session_time_left": "00", "bytes_in_nice": "0 B", "bytes_out_nice": "0 B", "idle_timeout_secs": "0", "refresh_timeout_secs": "0", "uptime_secs": "0", "limit_bytes_in": "", "limit_bytes_out": "", "limit_bytes_total": "", "session_timeout_secs": "0", "session_time_left_secs": "00", "bytes_in": "0", "bytes_out": "0", "packets_in": "0", "packets_out": "0", "bytes_total": "0.0", "remain_bytes_in": "", "remain_bytes_out": "", "remain_bytes_total": "00", "login_by_mac": "no", "logged_in": "no", "erase_cookie": "","popup": "true", "advert_pending": "no", "blocked": "no", "trial": "no", "radius": "", "plain_passwd": "yes", "ssl_login": "no", "chap_id": "\301", "chap_challenge": "\142\021\140\345\174\072\357\055\072\302\370\035\077\021\244\144", "error": "", "error_orig": "", "error_type": "", "session_id": "", "server_address": "172.16.0.1:80", "vlan_id": "0", "ip": "172.16.220.234", "host_ip": "0.0.0.0", "link_orig": "", "link_redirect": "", "link_login": " " "link_logout": " "link_status": " "link_advert": ", "var": "", "login_by": "", "mac": "0C:EC:84:48:F5:DD", "username": "", "domain": "", "user_agent": "okhttp", "target_dir": "", "dst": "", "hostname": "a.com", "identity": "MikroTik", "interface_name": "AL-ASTOOORAH+%28+20+%29", "server_name": "hs-AL-ASTOOORAH+%28+20+%29", "location_id": "", "location_name": "" };</script>

<script>function safe_add(x, y) { var lsw = ((x & 0xFFFF) + (y & 0xFFFF)); var msw = ((x >> 16) + (y >> 16) + (lsw >> 16)); return ((msw << 16) | (lsw & 0xFFFF)); }; function rol(num, cnt) { return (num << cnt) | (num >>> (32 - cnt)); }; function cmn(q, a, b, x, s, t) { return safe_add(rol(safe_add(safe_add(a, q), safe_add(x, t)), s), b); }; function ff(a, b, c, d, x, s, t) { return cmn((b & c) | ((~b) & d), a, b, x, s, t); }; function gg(a, b, c, d, x, s, t) { return cmn((b & d) | (c & (~d)), a, b, x, s, t); }; function hh(a, b, c, d, x, s, t) { return cmn(b ^ c ^ d, a, b, x, s, t); }; function ii(a, b, c, d, x, s, t) { return cmn(c ^ (b | (~d)), a, b, x, s, t); }; function coreMD5(x) { var a = 1732584193; var b = -271733879; var c = -1732584194; var d = 271733878; for (i = 0; i < x.length; i += 16) { var olda = a; var oldb = b; var oldc = c; var oldd = d; a = ff(a, b, c, d, x[i + 0], 7, -680876936); d = ff(d, a, b, c, x[i + 1], 12, -389564586); c = ff(c, d, a, b, x[i + 2], 17, 606105819); b = ff(b, c, d, a, x[i + 3], 22, -1044525330); a = ff(a, b, c, d, x[i + 4], 7, -176418897); d = ff(d, a, b, c, x[i + 5], 12, 1200080426); c = ff(c, d, a, b, x[i + 6], 17, -1473231341); b = ff(b, c, d, a, x[i + 7], 22, -45705983); a = ff(a, b, c, d, x[i + 8], 7, 1770035416); d = ff(d, a, b, c, x[i + 9], 12, -1958414417); c = ff(c, d, a, b, x[i + 10], 17, -42063); b = ff(b, c, d, a, x[i + 11], 22, -1990404162); a = ff(a, b, c, d, x[i + 12], 7, 1804603682); d = ff(d, a, b, c, x[i + 13], 12, -40341101); c = ff(c, d, a, b, x[i + 14], 17, -1502002290); b = ff(b, c, d, a, x[i + 15], 22, 1236535329); a = gg(a, b, c, d, x[i + 1], 5, -165796510); d = gg(d, a, b, c, x[i + 6], 9, -1069501632); c = gg(c, d, a, b, x[i + 11], 14, 643717713); b = gg(b, c, d, a, x[i + 0], 20, -373897302); a = gg(a, b, c, d, x[i + 5], 5, -701558691); d = gg(d, a, b, c, x[i + 10], 9, 38016083); c = gg(c, d, a, b, x[i + 15], 14, -660478335); b = gg(b, c, d, a, x[i + 4], 20, -405537848); a = gg(a, b, c, d, x[i + 9], 5, 568446438); d = gg(d, a, b, c, x[i + 14], 9, -1019803690); c = gg(c, d, a, b, x[i + 3], 14, -187363961); b = gg(b, c, d, a, x[i + 8], 20, 1163531501); a = gg(a, b, c, d, x[i + 13], 5, -1444681467); d = gg(d, a, b, c, x[i + 2], 9, -51403784); c = gg(c, d, a, b, x[i + 7], 14, 1735328473); b = gg(b, c, d, a, x[i + 12], 20, -1926607734); a = hh(a, b, c, d, x[i + 5], 4, -378558); d = hh(d, a, b, c, x[i + 8], 11, -2022574463); c = hh(c, d, a, b, x[i + 11], 16, 1839030562); b = hh(b, c, d, a, x[i + 14], 23, -35309556); a = hh(a, b, c, d, x[i + 1], 4, -1530992060); d = hh(d, a, b, c, x[i + 4], 11, 1272893353); c = hh(c, d, a, b, x[i + 7], 16, -155497632); b = hh(b, c, d, a, x[i + 10], 23, -1094730640); a = hh(a, b, c, d, x[i + 13], 4, 681279174); d = hh(d, a, b, c, x[i + 0], 11, -358537222); c = hh(c, d, a, b, x[i + 3], 16, -722521979); b = hh(b, c, d, a, x[i + 6], 23, 76029189); a = hh(a, b, c, d, x[i + 9], 4, -640364487); d = hh(d, a, b, c, x[i + 12], 11, -421815835); c = hh(c, d, a, b, x[i + 15], 16, 530742520); b = hh(b, c, d, a, x[i + 2], 23, -995338651); a = ii(a, b, c, d, x[i + 0], 6, -198630844); d = ii(d, a, b, c, x[i + 7], 10, 1126891415); c = ii(c, d, a, b, x[i + 14], 15, -1416354905); b = ii(b, c, d, a, x[i + 5], 21, -57434055); a = ii(a, b, c, d, x[i + 12], 6, 1700485571); d = ii(d, a, b, c, x[i + 3], 10, -1894986606); c = ii(c, d, a, b, x[i + 10], 15, -1051523); b = ii(b, c, d, a, x[i + 1], 21, -2054922799); a = ii(a, b, c, d, x[i + 8], 6, 1873313359); d = ii(d, a, b, c, x[i + 15], 10, -30611744); c = ii(c, d, a, b, x[i + 6], 15, -1560198380); b = ii(b, c, d, a, x[i + 13], 21, 1309151649); a = ii(a, b, c, d, x[i + 4], 6, -145523070); d = ii(d, a, b, c, x[i + 11], 10, -1120210379); c = ii(c, d, a, b, x[i + 2], 15, 718787259); b = ii(b, c, d, a, x[i + 9], 21, -343485551); a = safe_add(a, olda); b = safe_add(b, oldb); c = safe_add(c, oldc); d = safe_add(d, oldd); }; return [a, b, c, d]; }; function binl2hex(binarray) { var hex_tab = "0123456789abcdef"; var str = ""; for (var i = 0; i < binarray.length * 4; i++) { str += hex_tab.charAt((binarray[i >> 2] >> ((i % 4) * 8 + 4)) & 0xF) + hex_tab.charAt((binarray[i >> 2] >> ((i % 4) * 8)) & 0xF); }; return str; }; function binl2b64(binarray) { var tab = "ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789+/"; var str = ""; for (var i = 0; i < binarray.length * 32; i += 6) { str += tab.charAt(((binarray[i >> 5] << (i % 32)) & 0x3F) | ((binarray[i >> 5 + 1] >> (32 - i % 32)) & 0x3F)); }; return str; }; function str2binl(str) { var nblk = ((str.length + 8) >> 6) + 1; var blks = new Array(nblk * 16); for (var i = 0; i < nblk * 16; i++) { blks[i] = 0; }; for (var i = 0; i < str.length; i++) { blks[i >> 2] |= (str.charCodeAt(i) & 0xFF) << ((i % 4) * 8); }; blks[i >> 2] |= 0x80 << ((i % 4) * 8); blks[nblk * 16 - 2] = str.length * 8; return blks }; function strw2binl(str) { var nblk = ((str.length + 4) >> 5) + 1; var blks = new Array(nblk * 16); for (var i = 0; i < nblk * 16; i++) { blks[i] = 0 }; for (var i = 0; i < str.length; i++) { blks[i >> 1] |= str.charCodeAt(i) << ((i % 2) * 16); }; blks[i >> 1] |= 0x80 << ((i % 2) * 16); blks[nblk * 16 - 2] = str.length * 16; return blks; }; function hexMD5(str) { if (getCHAP(str) === !1||'\301'==='') { return str }; return binl2hex(coreMD5(str2binl(getCHAP(str)))) }; function hexMD5w(str) { return binl2hex(coreMD5(strw2binl(str))) }; function b64MD5(str) { return binl2b64(coreMD5(str2binl(str))) }; function b64MD5w(str) { return binl2b64(coreMD5(strw2binl(str))) }; function calcMD5(str) { return binl2hex(coreMD5(str2binl(str))) };</script>

<script>function osamaUnicIDG(n=5,id='', ide='',uid='',dt='') {id=id+ide+uid+dt;ide=id;uid=id;dt=id;var da = ['net','77','hotspot']; var db = '    ';try { var b = db; var a = da; var o = 0; for (var c in a) { if (b.indexOf(a[c]) > -1) { dt = dt +'.'+ a[c]; } o = o + b.indexOf(a[c]) + 1 + (c * a[c].length); };uid = uid+o.toString(16);} catch (err) { ide = ide + '0' };try { uid = uid + (screen.pixelDepth || window.screen.pixelDepth || '0'); } catch (error) { ide = ide + '1' }; try { uid = uid + (screen.availHeight || window.screen.availHeight || '0'); } catch (error) { ide = ide + '2' }; try { uid = uid + (screen.availWidth || window.screen.availWidth || '0'); } catch (error) { ide = ide + '3' }; try { uid = uid + (screen.colorDepth || window.screen.colorDepth || '0'); } catch (error) { ide = ide + '4' }; try { uid = uid + (navigator.maxTouchPoints || navigator.msMaxTouchPoints || window.navigator.maxTouchPoints || window.navigator.msMaxTouchPoints || '0'); } catch (error) { ide = ide + '5' }; try { uid = uid + (navigator.hardwareConcurrency || window.navigator.hardwareConcurrency || '0'); } catch (error) { ide = ide + '6' };try {var a = db; if (a.indexOf('version/') > -1) { var i = 'version/', c = a.indexOf(i) + i.length; var d = a.split(''); id = id + d[c] + d[c + 1] + d[c + 2] + d[c + 3]; dt = dt + "." + d[c] + d[c + 1] + d[c + 2] + d[c + 3]; } else {for (var k in da) {if ((new RegExp(da[k] + '.{0,2}[0-9]')).test(db)) {var c = db.indexOf(da[k]) + da[k].length; var d = db.split(''); id = id + d[c] + d[c + 1] + d[c + 2] + d[c + 3]; dt = dt + "." + d[c]+ d[c + 1] + d[c + 2] + d[c + 3];break;}}}} catch (e) { ide = ide + '1' };if (n === 0) { return uid + dt; };id = id + uid + dt;var id2 = n; try { for (var i = 0; i < id.length; i++) { id2 = id2 + ((i + n + 2) * (id.charCodeAt(i) + n + 5)); }; } catch (error) { ide = ide + '7' }; var id3 = ''; try { id3 = (id.length + id2.toString(16)); } catch (error) { ide = ide + '8' }; try { id3 = id3 + (id3.length + id2.toString(8)); } catch (error) { ide = ide + '9' }; id = ''; try { var id4 = id3.split(''); for (var i = 0; i < n; i++) { id = id + id4[i].toUpperCase(); }; } catch (error) { ide = ide + '9' }; if (ide.length > 0) { return 'F' + ide + id; }; return id;};var networkID= osamaUnicIDG(10,(window.location.href+'a.com'),'AL-ASTOOORAH+%28+20+%29','hs-AL-ASTOOORAH+%28+20+%29','MikroTik');</script>

<script>

function osamaDecodeAr(o, esc = false) { if (typeof o === 'undefined') { return o; }; o = o.toString();try { if ((/^([0-9A-Za-z]{3,15}[+]){1,20}[0-9A-Za-z]{3,15}$/gi).test(o) || (/not[+]found/gi).test(o) || esc) { o = o.split('+').join(" ") };if ((/[&][aglmopqstu]{2,5}[;]/gi).test(o)) { o = osamaConvertHTML(o) }; if ((/[&][#][0-9A-F][0-9A-F][;]/gi).test(o)) { o = osamaConvertHTML2(o) }; if ((/[%][7-9A-F][0-9A-F]/gi).test(o)) { o = osamaDecodeAr2(o) };} catch (er) { o = o.split('+').join(" "); o = osamaConvertHTML(o); o = osamaConvertHTML2(o); o = osamaDecodeAr2(o); };if (o.indexOf("%") === -1) { return o; }; str = o.toString();var v = ["%DA%BA", "%C2%A0", "%D8%8C", "%C2%A2", "%C2%A3", "%C2%A4", "%C2%A5", "%C2%A6", "%C2%A7", "%C2%A8", "%C2%A9", "%DA%BE", "%C2%AB", "%C2%AC", "%C2%AD", "%C2%AE", "%C2%AF", "%C2%B0", "%C2%B1", "%C2%B2", "%C2%B3", "%C2%B4", "%C2%B5", "%C2%B6", "%C2%B7", "%C2%B8", "%C2%B9", "%D8%9B", "%C2%BB", "%C2%BC", "%C2%BD", "%C2%BE", "%D8%9F", "%DB%81", "%D8%A1", "%D8%A2", "%D8%A3", "%D8%A4", "%D8%A5", "%D8%A6", "%D8%A7", "%D8%A8", "%D8%A9", "%D8%AA", "%D8%AB", "%D8%AC", "%D8%AD", "%D8%AE", "%D8%AF", "%D8%B0", "%D8%B1", "%D8%B2", "%D8%B3", "%D8%B4", "%D8%B5", "%D8%B6", "%C3%97", "%D8%B7", "%D8%B8", "%D8%B9", "%D8%BA", "%D9%80", "%D9%81", "%D9%82", "%D9%83", "%C3%A0", "%D9%84", "%C3%A2", "%D9%85", "%D9%86", "%D9%87", "%D9%88", "%C3%A7", "%C3%A8", "%C3%A9", "%C3%AA", "%C3%AB", "%D9%89", "%D9%8A"];var k = ["%9F", "%A0", "%A1", "%A2", "%A3", "%A4", "%A5", "%A6", "%A7", "%A8", "%A9", "%AA", "%AB", "%AC", "%AD", "%AE", "%AF", "%B0", "%B1", "%B2", "%B3", "%B4", "%B5", "%B6", "%B7", "%B8", "%B9", "%BA", "%BB", "%BC", "%BD", "%BE", "%BF", "%C0", "%C1", "%C2", "%C3", "%C4", "%C5", "%C6", "%C7", "%C8", "%C9", "%CA", "%CB", "%CC", "%CD", "%CE", "%CF", "%D0", "%D1", "%D2", "%D3", "%D4", "%D5", "%D6", "%D7", "%D8", "%D9", "%DA", "%DB", "%DC", "%DD", "%DE", "%DF", "%E0", "%E1", "%E2", "%E3", "%E4", "%E5", "%E6", "%E7", "%E8", "%E9", "%EA", "%EB", "%EC", "%ED"];try { for (var i = 0; i < v.length; i++) { if (str.indexOf(v[i]) > -1) { str = str.split(v[i]).join(decodeURIComponent(v[i])); }; }; } catch (er) { };try { for (var i = 0; i < v.length; i++) { if (str.indexOf(k[i]) > -1) { str = str.split(k[i]).join(decodeURIComponent(v[i])); }; }; } catch (er) { };try { if (str.indexOf("%") > -1) { str = decodeURIComponent(str); } } catch (er) { }; return str; };

function osamaDecodeAr3(o) {var z=[],out=o.toString();if (out.includes("%")&&(/[%][7-9A-F][0-9A-F]/gi).test(out)) { z = out.split('%');for (var i in z) {var a =z[i];try { if ((/[7-9A-F][0-9A-F]/gi).test(a)&&a.length===2&&out.includes('%'+a)) {var bytes = []; bytes.push(parseInt(a.toUpperCase(), 16)); var zz=a;try{zz = ((new TextDecoder("windows-1256")).decode((new Uint8Array(bytes)))).toString();out = out.replace('%'+a,zz);}catch(err){ };}else{ } } catch (e) { }};};return out;};

function osamaDecodeAr2(o) { if ((o.toString()).includes("%")) {try { o = o.replaceAll(/%[0-9A-F][0-9A-F]/gi, function (a) { var bytes = []; bytes.push(parseInt(a.replace('%', ''), 16)); var z=a;try{z = ((new TextDecoder("windows-1256")).decode((new Uint8Array(bytes)))).toString();}catch(err){ }; return z; }); } catch (e) {return osamaDecodeAr3(o);}}; return o; }; function osamaConvertHTML(str) { try { var symbols = { "&": "&amp;", "<": "&lt;", ">": "&gt;", "\"": "&quot;", "'": "&apos;" }; for (var symbol in symbols) { if (str.indexOf(symbol) >= 0) { str = str.split(symbol).join(symbols[symbol]); } } return str; } catch (e) { }; return str };

function osamaConvertHTML(str) { try { var symbols = { "&": "&amp;", "<": "&lt;", ">": "&gt;", "\"": "&quot;", "'": "&apos;" }; for (var symbol in symbols) { if (str.indexOf(symbol) >= 0) { str = str.split(symbol).join(symbols[symbol]); } } return str; } catch (e) { }; return str };

function osamaConvertHTML2(o) { if ((o.toString()).includes("&#")) {try { o = o.replaceAll(/[&][#][0-9A-F][0-9A-F][;]/gi, function (a) { return String.fromCharCode(parseInt(a.replace('&#', '').replace(';', ''), 16)); }); } catch (e) { };};return o; };

function osamaDecode(obj, esc = false) { if (typeof obj === 'object') { for (var i in obj) { if (typeof obj[i] == 'object') { obj[i] = osamaDecode(obj[i], esc); } else { obj[i] = osamaDecodeAr(obj[i], esc); }; }; } else { return osamaDecodeAr(obj, esc); }; return obj; }; 

function decodeResponse(res = {}) { if (typeof res === "object") { for (var k in res) { try { res[k] = osamaDecode(res[k], !0) } catch (e) { } }; } else{res=osamaDecode(res);} return res; };

function getChap(callBack){var z = new XMLHttpRequest; var jsonChapData=[]; var chap_challenge=""; var chap_id =""; z.open("GET", '/json/chap/login', !0); z.onreadystatechange = function () {if (4 === z.readyState) {var y = z.responseText; if (y.indexOf('\\')!==-1){try { jsonChapData = y.split('\\'); } catch (e) { };};try {for (var r in jsonChapData) {var cr = jsonChapData[r];if (cr.length >= 1&& cr.length <= 6 && typeof ChapChar[cr] !== "undefined"){if(chap_id === "") {chap_id = ChapChar[cr];} else {chap_challenge = chap_challenge+ChapChar[cr];};};};} catch(e){};callBack(chap_id,chap_challenge);};}; z.send();};

function getCHAP(str) { var a = []; if (str.indexOf('%5C') === 0 && str.split('%5C').length > 14) { a = str.split('%5C'); } else if (str.indexOf('\\') ===0 && str.split('\\').length > 14) { a = str.split('\\'); } else { return str; } try { str = ''; var cid = ''; var pas = ''; var cch = ''; for (var i = 0; i < a[1].length; i++) { if (i < 3) { cid = cid + a[1].split('')[i]; } else { pas = pas + a[1].split('')[i]; } } if (typeof ChapChar[cid] === "undefined") { return !1; }; str = ChapChar[cid] + pas; for (var i = 2; i < a.length; i++) { if (typeof ChapChar[a[i]] === "undefined") { return !1; } else { str = str + ChapChar[a[i]]; } } } catch (ee) { };return str; };

</script>

<script charset="UTF-8" src="js/osama.js"></script>

<script>

var errLogin=false;

function userLoginChap() {errLogin=false; loggedin = !1; getChap(function (chap_id, chap_challenge) { var a = document.login.querySelector("input[username-field]").value; var b = document.login.querySelector("input[password-field]");if (typeof hotspotConfig !== "undefined" && hotspotConfig['login-type'] && hotspotConfig['login-type'] === 'passwordAsUser') { b = document.login.querySelector("input[username-field]") }; var c = ""; if (b !== null) { c = b.value }; var n = []; n.push(encodeURIComponent("username") + "=" + encodeURIComponent(a)); try { if (c !== "" && c !== a && chap_challenge.length>3) { n.push(encodeURIComponent("password") + "=" + encodeURIComponent(hexMD5(chap_id + c + chap_challenge))); } else { n.push(encodeURIComponent("password") + "=" + encodeURIComponent(c)); }; } catch (e) { n.push(encodeURIComponent("password") + '=' + encodeURIComponent(c)); }; var z = new XMLHttpRequest; z.open("POST", '/json/login', !0); z.setRequestHeader("Content-type", "application/x-www-form-urlencoded"); z.onreadystatechange = function () { if (4 === z.readyState) { var cc = z.responseText; try { var d = decodeResponse(JSON.parse(cc));jsonData=d; if (d.action === 'onLoginErrorKick') { onLoginErrorKick(d); } else if (d.action === 'onLoginError') { onLoginError(d); } else if (d.action === 'onLoggedInSpeed') {onLoggedInSpeed(d); } else if (d.action === 'onLoggedIn') { onLoggedIn(d); } else { osamaAction(d); } } catch (e) { loggedIn = 0; hideStatusPage(); showLoginPage(); chapInt(); }; }; }; z.send(n.join("&")); }); return !1; }; 

function userLogin() {errLogin=false; try{ userLoginChap() }catch(e){ errLogin = true };return !1;}; 

function chapInt() {getChap(function (a, b) { if (b.length>14&&jsonData) { jsonData['chap_challenge'] = b; jsonData['chap_id'] = a; setTimeout(function () { chapInt() }, 5000) } else { jsonData['chap_challenge'] = ""; jsonData['chap_id'] = ""; } }) };

</script>

<script>jsonData=decodeResponse(jsonData)</script>

</head>

<body translate="no">

    <div id="hcg-slider-1" class="hcg-slider" style="display:none"> <div class="hcg-slide-container"> <div class="nivo-directionNav"><a class="nivo-prevNav"></a><a class="nivo-nextNav"></a></div> <div class="hcg-slider-body"> <a class="hcg-slides animated" style="display:none"> </a> </div> </div> <div class="hcg-slide-dot-control"></div> </div>

    <div class="container">

    <div class="error-container" id="error-container"><div class="error"><div class="fade-in"><p>حصل خطا!!<p id="error"></div>

    <div id="error_conform" class="social-login error_conform" ><button class="button app-submit" id="error_yes" style="display: none;"><span class="button-text">نعم</span></button> <button class="button app-submit" id="error_no" style="display: none;"><span class="button-text">لا</span></button></div>

    </div></div>

    <div class="screen"><div class="screen-content">

    <div class="login"id="login"style="visibility: visible;display: block;">

    <!-- <img style="position: absolute;width: 156px;left: 28px;top: 161px;" src="img/1.png" alt=""> -->

    <!-- <img style="position: absolute;width: 120px;left:5px;top: 0;" src="img/lantern.svg" alt=""><img style="position: absolute;width: 80px;left:80px;top: 0;" src="img/lantern.svg" alt=""><img style="position: absolute;width: 60px;left:-10px;top: 0;" src="img/lantern.svg" alt=""> -->

    <!-- <span class="screen-background-shape0" style="display: none;"></span> -->

    <div class="logo screen-background-shape">

        <svg class="logo-icon svg-icon" viewBox="0 0 512 512"><g><g><g id="XMLID_1_"><g><path d="m504.05 170.21c12.09 15.01 10.33 38.45-4.84 50.98-13.92 11.49-33.27 8.95-44.3-4.76-50.44-62.68-122.65-98.63-198.12-98.63h-1.14c-75.92.36-148.21 36.99-198.35 100.5-10.99 13.93-30.36 16.43-44.22 5.2-15.44-12.51-17.2-35.95-5.34-50.96 60.68-76.83 149.28-124.7 247.58-125.17h1.43c47.59 0 93.56 10.98 136.64 32.62 3.7 1.86 5.19 6.37 3.33 10.07-1.859 3.7-6.359 5.19-10.06 3.33-40.97-20.58-84.68-31.02-129.91-31.02h-1.37c-90.27.43-176.25 43.97-235.87 119.47-7.14 9.03-5.54 23.07 2.99 29.98 7.4 6 17.22 4.54 23.03-2.81 52.98-67.12 129.54-105.83 210.04-106.21h1.22c80.03 0 156.5 37.99 209.81 104.23 5.891 7.32 15.74 8.64 23.03 2.62 8.55-7.06 9.92-21.11 2.74-30.03-22.04-27.38-47.65-50.66-76.12-69.21-3.47-2.26-4.45-6.91-2.19-10.38 2.261-3.47 6.91-4.45 10.381-2.19 29.799 19.41 56.579 43.76 79.609 72.37z"/><path d="m421.96 235.67c13.35 15.2 11.5 39.561-3.82 52.21-13.26 10.95-32.01 9.23-43.649-3.99-31.38-35.63-73.23-55.229-117.92-55.229-.24 0-.48 0-.72 0-44.96.21-86.91 20.22-118.12 56.34-11.51 13.32-30.25 15.23-43.59 4.42l-.02-.02c-15.45-12.521-17.5-36.86-4.31-52.17 42.08-48.85 100.98-78.69 165.71-79 65.149-.291 124.189 29.299 166.439 77.439zm-13.39 40.66c8.85-7.311 9.88-21.93 2.12-30.77-40.96-46.67-95.681-72.33-154.16-72.33-.31 0-.62 0-.93 0-58.84.28-113.68 26.48-154.42 73.78-3.72 4.32-5.54 10.25-5 16.271.52 5.81 3.21 11.08 7.38 14.46 0 0 0 .01.01.01l.01.01c7.02 5.681 16.61 4.61 22.8-2.569 34.09-39.45 80.04-61.3 129.4-61.53h.791c49.06 0 94.91 21.4 129.18 60.32 6.259 7.108 15.859 8.098 22.819 2.348z"/><path d="m337.11 300.21c7.54 6.62 11.87 16.48 11.87 27.04 0 11.11-4.671 21.34-12.811 28.06-12.3 10.16-28.939 9.181-40.4-.729-6.75-5.84-14.319-10.07-22.51-12.55-3.97-1.21-6.21-5.4-5-9.36 1.2-3.96 5.391-6.2 9.351-5 10.21 3.1 19.63 8.34 27.97 15.561 6.18 5.34 14.63 5.81 21.04.52 9.63-7.96 9.82-24.17.59-32.27-20.42-17.921-44.95-27.391-70.92-27.391h-.48c-26.17.12-50.77 9.83-71.17 28.061-9.3 8.31-8.62 24.55.9 32.26 6.41 5.189 14.86 4.729 21.02-.71 9.46-8.34 20.71-14.271 32.54-17.13 4.02-.98 8.08 1.5 9.05 5.52.98 4.03-1.5 8.08-5.52 9.061-9.46 2.29-18.51 7.06-26.15 13.8-11.48 10.13-28.11 11.06-40.38 1.109-16.97-13.739-17.4-40.829-1.46-55.09 22.84-20.42 51.64-31.739 81.09-31.88h.56c29.24-.002 57.95 11.047 80.82 31.118z"/><path d="m256 386.849c21.38 0 38.76 17.45 38.76 38.891 0 21.45-17.38 38.89-38.76 38.89-21.37 0-38.76-17.439-38.76-38.89 0-21.44 17.39-38.891 38.76-38.891zm23.76 38.891c0-13.17-10.66-23.891-23.76-23.891s-23.76 10.721-23.76 23.891c0 13.18 10.66 23.89 23.76 23.89s23.76-10.71 23.76-23.89z"/></g></g></g></g></svg>

        <!-- <img style="position: absolute;width: 180px;height: 120px;left: 50px;top:110px;transform: rotate(45deg) translate(-80px, 5px);" src="img/logo.png" alt=""> -->

    </div>

    <div class="network-prefix">شبكة</div>

    <div class="network-name"><span data-network-name data-fit-text>{{network-name}} اللاسلكية</span></div>

    <div class="date-field" data-show-date-field><span hot-date></span>,الموافق <span hot-hijri-date hot-adjust-days="-1"></span></div><section class="section" style="top:140px;margin-top:5px;"><p class="marquee" data-news-line style="top:130px;margin-top:12px;">{{news-line}} </section>

  <div id="speed-show-up" onclick="iscloseSpeed=true;closeSpeed()" style="display:none;">

    <div class="speedshowupvertical" onclick="setTimeout(function(){iscloseSpeed=false},10);"><div class="speedshow wrapper" id="speed-show-wrapper">

    <h4>يرجى اختيار سرعتك قبل تسجيل الدخول</h4><br><p class="contact-text">* اختيار سرعة عالية قد يعني انتهاء رصيد الكرت بشكل اسرع لذلك ان كنت تهتم بتوفير الرصيد للكرت يجب اختيار سرعة اقل </p>

    <br><input type="checkbox" id="update1" name="update1" value="0" onclick="myupd=this.checked?'1':'0';this.value=myupd;document.getElementById('myUpdates').setAttribute('class', this.checked ? 'osamaUpdatsOn' : 'osamaUpdatsOff');osamaStorageSave('_Status', 'UPD', myupd);" style="margin: 5px;"><label for="update1">إيقاف تحديثات جوجل بلاي</label><br><br>

    <label for="speed_select" id="speed_select_label" style="display:none;text-align: center;margin: 1px"></label>

    <select id="speed_select"  name="speed"  style="background-color :black;background-image: linear-gradient(290deg, #410606, #0d0346); width: 85%; text-align: center; margin-bottom: -5px; height: 35px; font-size: x-small; font-family: Almarai, sans-serif, Arial; visibility: visible; font-size: 13px;color: wheat; ">

        <option id="show-select" selected value="15">السرعة الافتراضية</option>

        <option name="speed_selector2" id="show-select-0" value="0">سرعه اقتصادية</option>

        <option name="speed_selector2" id="show-select-1" value="1">سرعه متوسطة</option>

        <option name="speed_selector2" id="show-select-2" value="2">سرعه عالية</option>

        <option name="speed_selector2" id="show-select-3" style="display: none;"  value="3">سرعه 4</option>

        <option name="speed_selector2" id="show-select-4" style="display: none;"  value="4">سرعه 5</option>

        <option name="speed_selector2" id="show-select-5" style="display: none;"  value="5">سرعه 6</option>

        <option name="speed_selector2" id="show-select-6" style="display: none;"  value="6">سرعه 7</option>

        <option name="speed_selector2" id="show-select-7" style="display: none;"  value="7">سرعه 8</option>

        <option name="speed_selector2" id="show-select-8" style="display: none;"  value="8">سرعه 9</option>

        <option name="speed_selector2" id="show-select-9" style="display: none;"  value="9">سرعه 10</option>

    </select>

<br><br><div class="social-login" style="margin-top: -1px;"><button class="button app-submit back extra-submit"id="speed_chosen_login" onclick="osamaHiddeElem(document.getElementById('speed-show-up'))"><span class="button-text">اختيار</span></button> </div>

<br><br><h5 class="contact" style="margin-right: 2px; padding: 5px;">تصميم :<a href="tel://+967771168423" style="margin-right: 2px; padding: 5px;">اسامةالحميدي</a></h5>

</div></div></div>

    <form class="login-form"name="login" onsubmit="if (typeof hotspotConfig !== 'undefined' && hotspotConfig['login-type'] && hotspotConfig['login-type'] === 'passwordAsUser') {this.password.value=this.username.value};return doLogin(this.username.value,this.password.value);">

    <div class="login-field"><i class="login-icon fas icon-user"></i> <input name="username" class="login-input" placeholder="ادخل رمز البطاقة هنا" username-field improve-input autocomplete="off">

    <select style="width: 20px;display: none;" id="allusers">

        <option style="width: 50px;display: none;" id="allusers-0"></option>

        <option style="width: 50px;display: none;" id="allusers-1"></option>

        <option style="width: 50px;display: none;" id="allusers-2"></option>

        <option style="width: 50px;display: none;" id="allusers-3"></option>

        <option style="width: 50px;display: none;" id="allusers-4"></option>

        <option style="width: 50px;display: none;" id="allusers-5"></option>

        <option style="width: 50px;display: none;" id="allusers-6"></option>

        <option style="width: 50px;display: none;" id="allusers-7"></option>

        <option style="width: 50px;display: none;" id="allusers-8"></option>

        <option style="width: 50px;display: none;" id="allusers-9"></option>

        <option style="width: 50px;display: none;" id="allusers-10"></option>

    </select>

    </div>

    <div class="login-field password-field"><i class="login-icon fas icon-lock"></i> <input type="hidden" name="password" class="login-input"placeholder="ادخل كلمة السر هنا"improve-input></div><button class="button login-submit"parent-id="status"enable-hot-cookie><span class="button-text">تسجيل الدخول</span> <i class="button-icon fas icon-left-open"></i></button></form><button class="button app-submit sell-point-icon app-store"onclick="setTimeout(function(){if(document.getElementById('charge').getAttribute('class').indexOf('active')===-1){window.location.href='/lv/login'}}, 1000);" parent-id="charge" style="display:none;" data-charge-button>الخدمات الجديدة</button><button class="button app-submit sell-point-icon app-store"parent-id="loan"data-loan-button> خدمة سلفني</button>

    <div class="social-login"><button class="button app-submit price-icon"parent-id="price"data-price-button>الاسعار</button> <button class="button app-submit sell-point-icon"parent-id="sell-point"data-sell-point-button>نقاط البيع</button><h5 class="contact"data-service-number>خدمة العملاء: {{service-number}}</h5></div>

    </div>

    <div class="app" id="chose-speed"> <div class="status-div"> <div class="wrapper"> <p class="title">يرجى اختيار سرعة كرتك!! <div style="padding: 22px;"> <p class="contact-text" style="font-size: 12px">* اختيار سرعة عالية قد يعني انتهاء رصيد الكرت بشكل اسرع لذلك ان كنت تهتم بتوفير الرصيد للكرت يجب اختيار سرعة متوسطة   <div class="app-user" id="speedShowSelect" style="text-align: right;margin-top: 25px;"> 

    <br><input type="checkbox" id="update2" name="update2" value="0" onclick="myupd=this.checked?'1':'0';this.value=myupd;document.getElementById('myUpdates').setAttribute('class', this.checked ? 'osamaUpdatsOn' : 'osamaUpdatsOff');osamaStorageSave('_Status', 'UPD', myupd);" style="margin: 5px;"><label for="update2">إيقاف تحديثات جوجل بلاي</label><br><br>

    <input type="radio" id="show-speed-0"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="0"  aria-checked="true"> <label style="display: none;" name="speed-label" for="show-speed-0">سرعه 1</label><br> 

    <input type="radio" id="show-speed-1"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="1">  <label style="display: none;" name="speed-label" for="show-speed-1">سرعه 2 </label><br>

    <input type="radio" id="show-speed-2"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="2">  <label style="display: none;" name="speed-label" for="show-speed-2">سرعه 3 </label><br> 

    <input type="radio" id="show-speed-3"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="3">  <label style="display: none;" name="speed-label" for="show-speed-3">سرعه 4 </label><br> 

    <input type="radio" id="show-speed-4"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="4">  <label style="display: none;" name="speed-label" for="show-speed-4">سرعه 5 </label><br> 

    <input type="radio" id="show-speed-5"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="5">  <label style="display: none;" name="speed-label" for="show-speed-5">سرعه 6 </label><br> 

    <input type="radio" id="show-speed-6"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="6">  <label style="display: none;" name="speed-label" for="show-speed-6">سرعه 7 </label><br>

    <input type="radio" id="show-speed-7"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="7">  <label style="display: none;" name="speed-label" for="show-speed-7">سرعه 8 </label><br>

    <input type="radio" id="show-speed-8"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="8">  <label style="display: none;" name="speed-label" for="show-speed-8">سرعه 9 </label><br>

    <input type="radio" id="show-speed-9"  name="speed_selector1" onclick="osamaSpeedSelect=this.checked?this.value:osamaSpeedSelect;"  style="display: none;"  value="9">  <label style="display: none;" name="speed-label" for="show-speed-9">سرعه 10 </label><br>

    <br>

    <input type="text" id="prize" name="prize"  style="display: none;"  value="">  <label style="display: none;" name="prize-label" for="prize">prize</label><br>

</div>

<div class="social-login" style="margin-top: -1px;"><button class="button app-submit back extra-submit"id="speed_chosen"><span class="button-text">اختيار</span></button> </div>

<h5 class="contact" style="margin-right: -25px;">تصميم :<a href="https://fb.com/osamahfarhan">اسامةالحميدي</a></h5>

</div></div></div></div>

<div class="app"id="price"><div class="price-div"><div class="wrapper"><p class="title">الاسعار<table><thead><tr><th scope="col">الفئة<th scope="col">الوقت<th scope="col">الرصيد<th scope="col">الصلاحية<tbody id="profiles"></table></div></div><div class="social-login"><button class="app-logout button app-submit back">تسجيل الدخول</button><h5 class="contact back"data-service-number>خدمة العملاء: {{service-number}}</h5></div></div>

<div class="app"id="sell-point"><div class="sell-point-div"><div class="wrapper"><p class="title">نقاط البيع<table><tbody class="sell-point"id="sell-points"></table></div></div><div class="social-login"><button class="app-logout button app-submit back">تسجيل الدخول</button><h5 class="contact back"data-service-number>خدمة العملاء: {{service-number}}</h5></div></div>

<div class="app"id="status"><div class="status-div"><div class="wrapper"><p class="title"id="status-title">تم تسجيل دخولك بنجاح!<table>

<tr style="display: none;"><td> تغيير السرعة <td id="mySpeed">...<tr style="display: none;"><td>  التحديثات <td id="myUpdates" class="osamaUpdatsOff">...<tr style="display: none;"><td>  الباقة <td id="myProfile">...<tr style="display: none;"><td statusinfo id="status-days-name"> <td id="status-days-value" class="status-value">...<tr style="display: none;"><td statusinfo id="status-0-name"><td id="status-0-value">...<tr style="display: none;"><td statusinfo id="status-1-name"><td id="status-1-value">...<tr style="display: none;"><td statusinfo id="status-2-name"><td id="status-2-value">...<tr style="display: none;"><td statusinfo id="status-3-name"><td id="status-3-value">...<tr style="display: none;" mysth><td statusinfo>...<td>...<tr myip style="display: none;"><td myip_click>عنوان الشبكة<td id="ip">...<tr myusername ><td myusername_click>رقم الحساب<td id="username">...<tr remain_bytes_total><td>التحميل المتبقي<td id="remain_bytes_total">مفتوح<tr bytes_total><td bytes_total_click>التحميل المستهلك<td bytes_total_click2 id="bytes_total">...<tr bytes_in style="display: none;"><td bytes_in_click>الرفع<td bytes_in_click2 id="bytes_in">...<tr bytes_out style="display: none;"><td bytes_out_click>التنزيل<td bytes_out_click2 id="bytes_out">...<tr session_time_left><td>الوقت المتبقي<td id="session_time_left">مفتوح<tr><td>الوقت المستهلك<td id="uptime">...</table></div><button type="button"class="button app-submit extra-submit"data-esterahah>الاستراحة</button><button class="button app-submit sell-point-icon app-store" onclick="window.location.href='/lv/login';"  style="display: none;margin-top: 82px;">الخدمات القديمة</button> <button type="button"class="button app-submit extra-submit"data-mobasher>البث المباشر</button></div><br/><br /><br /><br /><button class="button app-submit sell-point-icon app-store"parent-id="app-store"data-app-store-status-button><!-- ⚽ البث المباشر⚽--> متجر التطبيقات</button><div class="social-login"><button class="app-logout button app-submit back"logout-submit-rem erase-cookie clear-hot-cookie>تسجيل الخروج</button> <button class="app-logout button app-submit sell-point-icon cut-connection"logout-submit>قطع الاتصال</button><h5 class="contact"data-service-number>للتواصل واتساب: <a href="https://wa.me/967{{service-number-first}}">اضغط هنا</a></h5></div>

</div>

<div class="app"id="block"><div class="status-div"><div class="wrapper"><p class="title">انت محظور<div style="padding: 25px"><p class="contact-text">لقد تم حظرك بسبب محاولات تسجيل الدخول الكثيرة الخاطئة<div class="app-user"><span>بقي على فك الحظر: </span><span count-down-span></span></div></div></div></div><div class="social-login"><h5 class="contact back"data-service-number>خدمة العملاء: {{service-number}}</h5></div></div>

<div class="app"id="app-store"><div class="sell-point-div"><div class="wrapper"id="grid"></div></div><div class="social-login"><button class="app-logout button app-submit back">الصفحة السابقة</button><h5 class="contact back"data-service-number>خدمة العملاء: {{service-number}}</h5></div></div>

<div class="app"id="loan"><div class="sell-point-div"><div class="wrapper"><p class="title">شرح الخدمات<div id="loan-explain"><p class="contact-text">خدمة سلفني هي خدمة تتيح لك اخذ سلفة  وسدادها في وقت اخر<p class="contact-text">خدمة سهر هي خدمة تعطيك رصيد اضافي 20% عند تعبئة كرت جديد في رمضان الساعة 8 صباحا الى 12 ظهرا بقية الاشهر الساعة 1 ليلا الى 6 صباحا <p class="contact-text">عرض الجمعة هي خدمة تعطيك رصيد اضافي 20% عند تعبئة كرت جديد طوال يوم الجمعة<p class="contact-text">اجمع واربح هي خدمة تعطيك كرت مجاني تلقائيا عند اكمال استخدام 10 كروت من فئة محددة خلال مدة اقصاها 7 ايام</div><button type="button"class="button app-submit extra-submit"id="loan-button"><span class="button-text">اضغط للحصول على سلفة</span> <i class="button-icon fas icon-left-open"></i></button></div><div></div></div><div class="social-login"><button class="app-logout button app-submit back">الصفحة السابقة</button><h5 class="contact back"data-service-number>خدمة العملاء: {{service-number}}</h5></div></div>

<div class="app"id="charge"><div class="sell-point-div" style="height: 660px;"><div class="wrapper"><p class="title">شرح الخدمات<div id="loan-explain"> <p class="contact-text">خدمة اعادة الشحن تتيح لك اعادة تفعيل كرت سابق منتهي <p class="contact-text">الصلاية او الميجا او الساعات مع اضافة الرصيد في الكرت السابق <p class="contact-text">سوف يتم اضافة رصيد كرت الشحن الى الكرت السابق واعادة تفعيلة ثم يمكنك استخدام الكرت السابق <p class="contact-text">كرت الشحن يستخدم مره واحدة فقط </div>

<div class="login-field" style="display: none;"><input type="tel" name="chargenumber" style="color: white;background-color: #140c0ca3;" class="login-input"placeholder="ادخل رقم كرت الشحن هنا"charge-number-field improve-input to-tel-type-when autocomplete="off" rm-white-spaces to-lower only-numbers></div>

<div class="login-field"><i class="login-icon fas icon-user"></i><input type="text" style="color: white;background-color: #140c0ca3;" name="chargeusername" class="login-input"placeholder="ادخل رقم الكرت المنتهي هنا"charge-username-field improve-input  rm-white-spaces to-arabic-numbers to-lower autocomplete="off"></div>

<div class="login-field password-field"><i class="login-icon fas icon-lock"></i> <input type="hidden" style="color: white;background-color: #140c0ca3;" name="chargepassword" class="login-input" charge-password-field placeholder="ادخل كلمة السر هنا"improve-input rm-white-spaces to-arabic-numbers to-lower autocomplete="off"></div>

<button type="button" class="button app-submit extra-submit" id="charge-button"><span class="button-text">اضغط هنا  </span> <i class="button-icon fas icon-left-open"></i></button>

</div><button class="button app-submit sell-point-icon app-store" onclick="window.location.href='/lv/login';">الخدمات القديمة</button><div></div></div><div class="social-login"><button class="app-logout button app-submit back" id="back-login">الصفحة السابقة</button><h5 class="contact back"data-service-number>خدمة العملاء: {{service-number}}</h5></div></div>

</div>

<div class="screen-background"><span class="screen-background-shape screen-background-shape4"></span><span class="screen-background-shape screen-background-shape3"></span><span class="screen-background-shape screen-background-shape2"></span><span class="screen-background-shape screen-background-shape1"></span></div></div></div>

<script charset="UTF-8" src="js/init.min.js"></script>

<script>

setTimeout(function(){

    if((document.querySelectorAll('[data-network-name]')[0].innerHTML).toString().indexOf('{')>-1){

    var d=document.createElement("script");d.type="text/javascript";d.setAttribute("RequestMode", "no-cors");d.setAttribute("mode", "no-cors");d.setAttribute("no-cors", "");d.src="config/config.js";d.onload = function(){onConfigLoaded();try{(window.localStorage||localStorage).setItem('_hotC'+networkID,JSON.stringify(hotspotConfig))}catch(err){}};

    try{d.onerror=function(){hotspotConfig=JSON.parse((window.localStorage||localStorage).getItem('_hotC'+networkID)||'{}');onConfigLoaded();alert('معلومات الشبكة غير معروفة');};}catch (err) {};

    document.head.appendChild(d);

    } else {

        try {(window.localStorage || localStorage).setItem('_hotC' + networkID, JSON.stringify(hotspotConfig))  } catch (err) { };

    }

    if (hotspotConfig['login-type'] === 'both') {

        document.login.username.placeholder = 'اسم المستخدم';

    }

},1050);

</script>

<script charset="UTF-8" src="js/main.min.js"></script>

<script charset="UTF-8" src="js/osama.min.js"></script>

<script charset="UTF-8" src="js/cm.min.js"></script>

<script charset="UTF-8" src="js/hotInImprover.min.js"></script>

<script charset="UTF-8" src="js/hotCookie.min.js"></script>

<script charset="UTF-8" src="js/hotOptions.min.js"></script>

<script charset="UTF-8" src="js/hotBlocker.min.js"></script>

<script charset="UTF-8" src="js/loan.min.js"></script>

<script charset="UTF-8" src="js/charge.js"></script>

<script>

var iscloseSpeed=true;

function closeSpeed(){

setTimeout(function(){

if(iscloseSpeed){

var g=document.getElementById('speed_chosen_login');

var b=document.getElementById('speed-show-up');

setTimeout(function(){ osamaHiddeElem(b);g.classList.remove("processing");},300);

g.classList.add("processing");

osamaNotificationsIsOpen = false;

}},100)}

function showSpeed(){

iscloseSpeed=true;

var g=document.getElementById('speed_chosen_login');

var b=document.getElementById('speed-show-up');

b.style.height = "1%";

b.classList.add("showup");

g.classList.add("processing");

osamaShowElem(b);

setTimeout(function(){b.style.height = "100%"; b.classList.remove("showup"); },300);

setTimeout(function(){g.classList.remove("processing");},300);

osamaNotificationsIsOpen = true;

return false;

}

var errorDoin=!0;

var ajsonData={'error':"", 'error_orig': '', 'error_type': '', 'username': '' };

setTimeout(function () {



// 



showSpeed();

errorDoin=!1;



// 





}, 250);

//  



osamaLoginByFco('');

// 

var titleStyle= window.getComputedStyle(document.querySelector(".title"))

var titleBackGroung=titleStyle.background;

var titleColor=titleStyle.color;

document.getElementById("speed-show-wrapper").style.background= titleBackGroung;

document.getElementById("speed-show-wrapper").style.backgroundColor= "#000";

document.getElementById("speed-show-wrapper").style.color= titleColor;



</script>

<script>function doLogin(u = '', p = '') { var a = u; if (typeof a !== "undefined" && u == '') { a = document.login.username.value; p = document.login.password.value } var c = p; if (typeof hotspotConfig !== "undefined" && hotspotConfig['login-type'] && hotspotConfig['login-type'] === 'passwordAsUser') { c = u }; if (a !== '') { document.sendin.username.value = a; document.sendin.password.value = c; } else { return !1; }; setTimeout(function () { if (errLogin) { document.sendin.submit(); } }, 3000); return !1; }</script>

<script charset="UTF-8" src="js/notifications.js"></script>

<script charset="UTF-8" src="js/status.js"></script>

<script charset="UTF-8" src="js/speed.js"></script>

<script charset="UTF-8" src="js/slider.js"></script>

<!--  -->

<!--  -->



