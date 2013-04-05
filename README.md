raptorize
=========

Based on the Raptorize from ZURB's Playground (see link). An easy way to deliver to content via CDN and copy and paste without having to download and blog up a local server.

<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.4.3/jquery.min.js"></script>
<script>!window.jQuery && document.write('<script src="jquery-1.4.3.min.js"><\/script>')</script>
<script src="jquery.raptorize.1.0.js"></script>
<script type="text/javascript">
   $(window).load(function() {
      $('.button').raptorize({
        'enterOn' : 'click', //timer, konami-code, click
        'delayTime' : 5000 //time before raptor attacks on timer mode
   });
});
</script>
