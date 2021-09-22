# Helm Chart for Maian Music

Maian Music is a PHP application for selling digital and physical music

## Manual post install steps

After deployment, style sheets will be broken because the Maian Music app doesn't know its own URL.

1. Browse to the URL where you deployed Maian Music and add `/admin/index.php?p=settings` to the end of the path
1. Scroll down to **Store HTTP Path** and enter the fully qualified path to your site, taking care to specify `http://` or `https://` as appropriate
1. Set **Server Path to Secure Folder** as `/var/www/secure`
1. Click **Update**
