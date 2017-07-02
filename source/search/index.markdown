---
layout: page
title: "search"
date: 2017-07-02 13:31
comments: true
footer: true
---

<div>
<script>
  (function(){
    function getParameterByName(name) {
    name = name.replace(/[\[]/, "\\[").replace(/[\]]/, "\\]");
    var regex = new RegExp("[\\?&]" + name + "=([^&#]*)"),
        results = regex.exec(location.search);
    return results === null ? "" : decodeURIComponent(results[1].replace(/\+/g, " "));
    }
    document.getElementById('sitesearchtextbox').value = getParameterByName('q');
  })();

  (function() {
    var cx = '014681989174846030100:za8tmf4lz04';
    var gcse = document.createElement('script');
    gcse.type = 'text/javascript';
    gcse.async = true;
    gcse.src = 'https://cse.google.com/cse.js?cx=' + cx;
    var s = document.getElementsByTagName('script')[0];
    s.parentNode.insertBefore(gcse, s);
  })();
</script><gcse:searchresults-only></gcse:searchresults-only>
</div>
