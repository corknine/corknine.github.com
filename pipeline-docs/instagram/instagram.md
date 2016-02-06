Instagram Token Generator
================


<div class="generate-token">
  <p><a class="button" href="https://instagram.com/oauth/authorize/?client_id=c4d02e0d5f3d47168a966b69d93317de&amp;redirect_uri=http://corknine.com/pipeline-docs/instagram/&amp;response_type=token">Generate Access Token</a></p>
</div>

<div class="token-received" style="display:none">
  <p>Here's your access token, copy and paste this into your theme settings:</p>
  <p><input class="token" type="text" value="" /></p>
</div>

<script>
jQuery(function($) {
  token = window.location.hash.split("#access_token=")[1];

  if (token.length) {
    $('.generate-token').hide();
    $('.token-received').show();
  }

  $("input.token").val(token).on("click", function() {
    $(this).select();
  });
});
</script>

