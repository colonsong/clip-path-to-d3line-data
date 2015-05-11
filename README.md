# clip-path-to-d3line-data
&lt;polygon points="394 168,383 306,675 314,688 193,659 68,503 42,440 42"> 轉成d3 line data格式

用D3常需要用到line data 好比說
<pre>
var data = [
      {x:658,y:78},
      {x:616,y:114},
      {x:541,y:82},
      {x:463,y:112},
      {x:452,y:189},
      {x:509,y:242},
      {x:584,y:238},
      {x:630,y:199},
      {x:672,y:217},
      {x:610,y:279},
      {x:503,y:288},
      {x:414,y:207},
      {x:417,y:94},
      {x:523,y:46},
      {x:612,y:60},
      {x:616,y:61}
    ];
    
  var line = d3.svg.line()
    .x(function(d) {
      return d.x;
    })
    .y(function(d) {
      return d.y;
    }).interpolate('basis');
</pre>
怎麼快速的建立line data 可以去這個網站畫完
http://cssplant.com/clip-path-generator
在利用這隻正規轉成line data格式



