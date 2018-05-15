<!-- Modify this according to your requirement -->
<h3>
  Redirecting to romgatchalian.com after <span id="countdown">10</span> seconds
</h3>
<!-- JavaScript part -->
<script type="text/javascript">
    
    // Total seconds to wait
    var seconds = 5;
    
    function countdown() {
        seconds = seconds - 1;
        if (seconds < 0) {
            window.location = "https://romgatchalian.com";
        } else {
            document.getElementById("countdown").innerHTML = seconds;
            window.setTimeout("countdown()", 1000);
        }
    }
    
    // Run countdown function
    countdown();
    
</script>
