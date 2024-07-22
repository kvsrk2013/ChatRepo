<!DOCTYPE html>
<html>
  <style>
    html {
      background-repeat: norepeat;
      background-size: cover;
    }
  iframe{
    width: 100%;
    height:100%;
    border: none;
  }
  </style>
  <head>
    <title>Salesforce Chat - Iframes POC</title>
  </head>
  <!--
  <script type="text/javascript" src="path/to/prototype.js"></script> -->
  <script type="application/javascript">
    window.onmessage = function(e) {
      console.log(e.data.hasOwnProperty("frameHeight"));
      if (e.data.hasOwnProperty("frameHeight")) {
        var chatFrame = document.getElementById("chatFrame");
        chatFrame.style.height = e.data.frameHeight + 20 + "px";
        chatFrame.style.width = e.data.frameWidth + 20 + "px";
      }
    };
  </script>
  <body>
    <div style ="bottom: 0px; right: 0px; position: absolute;" >
      <iframe id="chatFrame" src= "https://github.com/kvsrk2013/ChatRepo/childpage_chat.html"></iframe>
    </div>
  </body>
  
</html>
