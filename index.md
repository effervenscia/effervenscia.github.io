<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" style="height: 0; position: absolute">
  <symbol id="youtube-fixed" viewBox="0 0 24 24"><path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z" fill-rule="nonzero"/></symbol>
  <symbol id="discord" viewBox="0 0 24 24"><path d="M20.222 0c1.406 0 2.54 1.137 2.607 2.475V24l-2.677-2.273-1.47-1.338-1.604-1.398.67 2.205H3.71c-1.402 0-2.54-1.065-2.54-2.476V2.48C1.17 1.142 2.31.003 3.715.003h16.5L20.222 0zm-6.118 5.683h-.03l-.202.2c2.073.6 3.076 1.537 3.076 1.537-1.336-.668-2.54-1.002-3.744-1.137-.87-.135-1.74-.064-2.475 0h-.2c-.47 0-1.47.2-2.81.735-.467.203-.735.336-.735.336s1.002-1.002 3.21-1.537l-.135-.135s-1.672-.064-3.477 1.27c0 0-1.805 3.144-1.805 7.02 0 0 1 1.74 3.743 1.806 0 0 .4-.533.805-1.002-1.54-.468-2.14-1.404-2.14-1.404s.134.066.335.2h.06c.03 0 .044.015.06.03v.006c.016.016.03.03.06.03.33.136.66.27.93.4.466.202 1.065.403 1.8.536.93.135 1.996.2 3.21 0 .6-.135 1.2-.267 1.8-.535.39-.2.87-.4 1.397-.737 0 0-.6.936-2.205 1.404.33.466.795 1 .795 1 2.744-.06 3.81-1.8 3.87-1.726 0-3.87-1.815-7.02-1.815-7.02-1.635-1.214-3.165-1.26-3.435-1.26l.056-.02zm.168 4.413c.703 0 1.27.6 1.27 1.335 0 .74-.57 1.34-1.27 1.34-.7 0-1.27-.6-1.27-1.334.002-.74.573-1.338 1.27-1.338zm-4.543 0c.7 0 1.266.6 1.266 1.335 0 .74-.57 1.34-1.27 1.34-.7 0-1.27-.6-1.27-1.334 0-.74.57-1.338 1.27-1.338z" fill-rule="nonzero"/></symbol>
</svg>

<h1>Here are my links.</h1>
<h2> Thank you.</h2>
<h1> Okay. </h1>
<b>This is my website.</b> <i>It is awesome.</i>


{% include button.html text="Twitch" icon="twitch" link="https://twitch.tv/effervenscia" color="#9146FF" %} {% include button.html text="Twitter" icon="twitter" link="https://twitter.com/effervenscia" color="#1DA1F2" %} {% include button.html text="YouTube" icon="youtube-fixed" link="https://www.youtube.com/channel/UCJWHqSk91IklDBG6BtlL4UQ" color="#FF0000" %}{% include button.html text="Discord" icon="discord" link="https://discord.com/invite/nz4FUNQ" color="#7289DA" %}

<script src= "https://player.twitch.tv/js/embed/v1.js"></script>
<div id="Twitch-Player"></div>
<script type="text/javascript">
  var options = {
    width: "100%",
    channel: "Effervenscia",

    parent: ["effervenscia.com"]
  };
  var player = new Twitch.Player("Twitch-Player", options);
  player.setVolume(0.5);
</script>
