# Costa Huang's Website

## What's different than the default template

This repo allows you to use a different page as the default route `index.html` and the generated blog page will be place at `blog.html`

Assuming you setup your index page with url `blog` (example: https://www.notion.so/043f2251b5db4aaba615a8d703455d8c?v=157e166961ff4f06acd38b02cc148fe1), run the following command


```
git clone https://github.com/vwxyzjn/notablog-starter.git && cd notablog-starter
# replace the `url` of the `config.json` to be your page (e.g. https://www.notion.so/043f2251b5db4aaba615a8d703455d8c?v=157e166961ff4f06acd38b02cc148fe1)
npm i -g vwxyzjn_notablog
notablog generate .
bash posthook.sh
notablog preview .
```

If you are confused with my instructions, checkout instructions from https://github.com/dragonman225/notablog