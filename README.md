Originally based on the bundle provided in [jinja2/ext](https://github.com/mitsuhiko/jinja2/tree/master/ext).

Before installing, be sure to remove the original bundle, or you may experience key collisions.

Then, to install:

<pre>
  mkdir -p ~/Library/Application\ Support/TextMate/Bundles
  cd ~/Library/Application\ Support/TextMate/Bundles
  git clone git://github.com/ozan/textmate-jinja-templates.git "Jinja Templates.tmbundle"
  osascript -e 'tell app "TextMate" to reload bundles'
</pre>