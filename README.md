# fool
  
    <div style="text-align:center;">
    <h1>Thank you!</h1>
    <h2> <p>We are submiting your request.</p></h2>
    <span id="timer">
    </span>
    </div>
    <script type="text/javascript">
    var count = 10;
    var redirect = "https://form.jotform.com/91607224171956";
     
    function countDown(){
        var timer = document.getElementById("timer");
        if(count > 0){
            count--;
            timer.innerHTML = "This will be submitted in "+count+" seconds.";
            setTimeout("countDown()", 1000);
        }else{
            window.location.href = "doublethank.html";
        }
    }
    countDown();
    </script>
    
      
      
