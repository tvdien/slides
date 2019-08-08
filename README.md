All slides is written with asciidoc and `reveal.js`. Since these are my memo as a result of self-study, so something may be wrong.

### How to see slide

- `git clone this repository`
- `ruby -run -e httpd out -p 5000 -b 0.0.0.0`

### How to write something

- Add slide into `src/topic_name/slide_name.adoc` . If you want to use image in a slide, add these image into `src/assets/topic_name/image.png`
- `bundle exec asciidoctor-revealjs -a revealjsdir=/reveal.js src/topic_name/slide_name.adoc -o out/topic_name/slide_name.html`
