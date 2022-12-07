# component-renderer-out

Specify html by json and render out. This repo is just source of tests...

List of all available spec/html is here:   
https://raw.githubusercontent.com/hopocode/component-renderer-out/main/list.json

**!!! Children must be list of child !!!**


## Child can be
- element (has property ```el``` and optional ```attrs``` and ```children```)
- content (has property ```content``` and optional ```escape``` which can be ```noescape``` or by default ```escape_html```)
- text_content (is typeof string)

