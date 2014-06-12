---
layout: post
title: Hasznos bookmarkletek
description: Segítség a mindennapokban
modified: {}
tags: 
  - bookmarklet
image: 
  feature: "abstract-3.jpg"
  credit: dargadgetz
  creditlink: "http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/"
comments: true
share: true
published: true
---


Munkavédelmi "Megoldom" ellenőrző gomb

<div markdown="0"><a onclick="window.alert('Egyszerűen csak húzd a linket az eszköztárra és használd a megfelelő weboldalon :) ...');return false;"  href="javascript:(function(){for(var a=document.getElementsByTagName(&quot;input&quot;),b=0;b&lt;a.length;b++)&quot;radio&quot;==a[b].type&amp;&amp;0&lt;a[b].value&amp;&amp;(a[b].checked=&quot;checked&quot;);})();" class="btn btn-success">Megoldom</a></div>

Worktime "számolóka"

<div markdown="0"><a onclick="window.alert('Egyszerűen csak húzd a linket az eszköztárra és használd a megfelelő weboldalon :) ...');return false;" href="javascript:(function(){(function(){javascript:(function(){$x=function(i){var%20b=document,d=[];try{for(var%20e=b&amp;&amp;b.ownerDocument||window.document,j=e.evaluate(i,b||e,null,XPathResult.ANY_TYPE,null),f;f=j.iterateNext();)d.push(f)}catch(k){throw%20k;}return%20d};for(var%20a=$x(&quot;//td[@class%20=%20'tblHeader'%20and%20contains(text(),'Total%20Time')]/../td[not(@class)%20and%20normalize-space(text())%20!=%20'']&quot;),c=$x(&quot;//td[@class%20=%20'tblHeader'%20and%20contains(text(),'Regular%20Time')]/../td[not(@class)%20and%20normalize-space(text())%20!=%20'']&quot;).length,g=0,h=0;h&lt;a.length;h++)var%20l=a[h].innerHTML.match(/(\d+)(:(\d\d))?\s*(p?)/),g=g+(60*l[1]+1*l[3]);g-=480*c;alert(g+&quot;%20perc&quot;);})();})();})();" class="btn btn-success">Számolóka</a></div>

Redmine "kell" gomb

<div markdown="0"><a onclick="window.alert('Egyszerűen csak húzd a linket az eszköztárra és használd a megfelelő weboldalon :) ...');return false;" href='javascript:(function(){(function(){if(window.jQuery===undefined){var%20done=false;var%20script=document.createElement("script");script.src="//code.jquery.com/jquery-git.js";script.onload=script.onreadystatechange=function(){if(!done&&(!this.readyState||this.readyState=="loaded"||this.readyState=="complete")){done=true;initMyBookmarklet();}};document.getElementsByTagName("head")[0].appendChild(script);}else{initMyBookmarklet();}function%20initMyBookmarklet(){(function(){jQuery("#update").show();jQuery("#issue_assigned_to_id").val(jQuery("#loggedas%20a").attr("href").slice(7));jQuery("#issue_fixed_version_id").val("");jQuery("#issue_custom_field_values_8").val("");jQuery("#issue_status_id").val(2);})();}})();})();' class="btn btn-success">Kell</a></div>

Redmine ticket counter

<div markdown="0"><a onclick="window.alert('Egyszerűen csak húzd a linket az eszköztárra és használd a megfelelő weboldalon :) ...');return false;" href='javascript:(function(){var%20url="/my/page?";if(!document.getElementById("mokus")){var%20ifrm=document.createElement("iframe");ifrm.setAttribute("src",url+Math.random().toString());ifrm.setAttribute("id","mokus");ifrm.style.width="4px";ifrm.style.height="4px";document.body.appendChild(ifrm);}document.getElementById("mokus").onload=function(){var%20a=document.createElement("canvas"),b,d=document.createElement("img"),e=document.head.getElementsByTagName("link")[0].cloneNode(!0),c=document.getElementById("mokus").contentDocument.getElementById("list-top").getElementsByTagName("h3")[0].innerHTML.match(/\((\d+)\)/)[1];a.getContext&&(a.height=a.width=16,b=a.getContext("2d"),d.onload=function(){b.drawImage(this,0,0);b.font="bold%2010px%20\"helvetica\",%20sans-serif";b.fillStyle="#F0EEDD";1==c.length&&(c="0"+c);b.fillText(c,2,12);e.href=a.toDataURL("image/png");document.body.appendChild(e);},d.src="/favicon.ico");};var%20mokustimer=setInterval(function(){document.getElementById("mokus").setAttribute("src",url+Math.random().toString());},1E4);})();' class="btn btn-success">RTC</a></div>