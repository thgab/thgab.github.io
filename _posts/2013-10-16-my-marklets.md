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

<div markdown="0"><a onclick="window.alert('Egyszerűen csak húzd a linket az eszköztárra és használd a megfelelő weboldalon :) ...');return false;" href='javascript:void((function(){jQuery("#update").show();jQuery("#issue_assigned_to_id").val(jQuery("#loggedas%20a").attr("href").slice(7));jQuery("#issue_fixed_version_id").val("");jQuery("#issue_custom_field_values_8").val("");jQuery("#issue_status_id").val(2);})());' class="btn btn-success">Kell</a></div>