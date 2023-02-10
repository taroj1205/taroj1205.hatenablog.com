---
title: 日本語と英語の切り替えが楽になるツールの紹介。
date: 2020-12-04T09:39:32.000Z
categories:
  - 紹介
  - 紹介-ツール
id: "26006613660313675"
draft: false
---
こんにちは。ニュージーランドに住んでいる14歳の太朗です。

<strong><u>これは僕の14歳での最後のブログです。</u></strong>


<marquee height="30" width="400" behavior="alternate" direction="right" scrollamount="3" truespeed>
<b><span style="font-size: 120%">明日は僕の15歳の誕生日です！！！！</b></strong>
</marquee>

今日は英語キーボードで日本語と英語の切り替えが楽になるツールを紹介します。

<b style="color: red;">⚠Windows以外では使えません⚠</b>


[:contents]


##どういうツールなの？


<!-- more -->


<a href="#explain" onclick="highlightYellow()" style="color: #33403d;">上</a>で説明した通り、このツールはキーボードの<strong>[Alt]</strong>キーの右と左で日本語入力と英語入力に簡単に切り替えることが出来ます。

##インストール
ではインストールする説明をします。
###ダウンロード
1. まず、Githubのダウンロードページヘ行きます。
[https://github.com/karakaram/alt-ime-ahk/releases:embed:cite]
###解凍
1. alt-ime-ahk.zipというのをクリックします。
[f:id:taroj1205:20201204133418p:plain]
1. 次にZipファイルを開きExtract（解凍）します。
[f:id:taroj1205:20201204161010p:plain]
1. 1. Show extracted files when completeをチェック。（解凍が終わったら開く）
   1. そしてExtract（解凍）をクリック。
[f:id:taroj1205:20201204162932p:plain]
###起動
1. 解凍が終わったら「alt-ime-ahk.exe」をダブルクリックして開く。
[f:id:taroj1205:20201204182806p:plain]

<strong>実行したらタスクトレイに常駐されるはずです。</strong>

##起動したときに自動で実行させる方法。
1. まず、[Windows]+[r]を押し、そこに、「
<input type="text" value="%appData%\Microsoft\Windows\Start Menu\Programs\Startup" id="myInput"><div class="tooltip">　<button onclick="myFunction()" onmouseout="outFunc()">
  <span class="tooltiptext" id="myTooltip">クリップボードにコピー</span>
  コピー
  </button>
</div>」を貼り付け送る。<br />

1. 次に、先程実行した、「alt-ime-ahk.exe」をそこに貼り付けます。

##感想
今まで、日本語と英語を切り替えるには、[Shift]+[Caps Lock]か、[Alt]+[`]しか出来ませんでした。

僕は何回も日本語と英語を切り替えるので大変でした。

でも、このツールを使うことで、素早く切り替えることができ、ブログなどを書くのがとても速くなりました。

##作った方の記事
このとても役に立つツールを作ってくれた方のブログを紹介します。<br />
<b>作っていただきありがとうございます！</b>
[https://www.karakaram.com/alt-ime-on-off/:embed:cite]

<br />
Facebookなどでシェアお願いします！<br />

<br />

<hr />

クリックしていただけると嬉しいいです！<br />
<a href="https://overseas.blogmura.com/ranking/in?p_cid=10927073" target="_blank" ><img src="https://b.blogmura.com/overseas/88_31.gif" width="88" height="31" border="0" alt="にほんブログ村 海外生活ブログへ" /></a>
<a href="https://overseas.blogmura.com/cebu/ranking/in?p_cid=10927073" target="_blank" ><img src="https://b.blogmura.com/overseas/cebu/88_31.gif" width="88" height="31" border="0" alt="にほんブログ村 海外生活ブログ セブ島情報へ" /></a>
<a href="https://overseas.blogmura.com/newzealand/ranking/in?p_cid=10927073" target="_blank" ><img src="https://b.blogmura.com/overseas/newzealand/88_31.gif" width="88" height="31" border="0" alt="にほんブログ村 海外生活ブログ ニュージーランド情報へ" /></a>
<a href="https://blogmura.com/ranking/in?p_cid=10927073" target="_blank"><img src="https://b.blogmura.com/88_31.gif" width="88" height="31" border="0" alt="ブログランキング・にほんブログ村へ" /></a>
<a href="https://blogmura.com/profiles/10927073?p_cid=10927073"><img src="https://blogparts.blogmura.com/parts_image/user/pv10927073.gif"  width="80" height="43.5" border="0" alt="PVアクセスランキング にほんブログ村" /></a>

<script>
   function highlightYellow() {
       document.getElementById("y").style.color = "white";
       document.getElementById("y").style.backgroundColor = "black";
   }

function myFunction() {
  var copyText = document.getElementById("myInput");
  copyText.select();
  copyText.setSelectionRange(0, 99999);
  document.execCommand("copy");
  alert("コピーしました。");
  
  var tooltip = document.getElementById("myTooltip");
  tooltip.innerHTML = "Copied: " + copyText.value;
}

function outFunc() {
  var tooltip = document.getElementById("myTooltip");
  tooltip.innerHTML = "クリップボードにコピー";
}
</script>
