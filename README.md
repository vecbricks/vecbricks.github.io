# vecbricks.github.io

Engineering notes from [Varka](https://github.com/vecbricks/varka), a research
fork of Apache Spark that compiles a whole projection into one vector loop and
runs it over Arrow columns, inside the JVM.

Each post is a build product, not a hand-edited page. The prose lives in the
Varka repository as Markdown, the figures are short Python scripts that render
themselves to SVG, and `dev/varka_post_page.py` turns the two into the page
published here. So a number in a post traces to a committed benchmark results
file, and a drawing traces to the script that drew it; neither can drift from
what the repository says.

    dev/varka_post_page.py sql/varka/plans/POST_MILESTONE_5.md \
      --out <this repo>/eight-rows-per-instruction \
      --og-image https://vecbricks.github.io/eight-rows-per-instruction/card.png

    dev/varka_post_page.py sql/varka/plans/POST_MILESTONE_6_SPARK.md \
      --out <this repo>/the-8000-byte-cliff \
      --og-image https://vecbricks.github.io/the-8000-byte-cliff/card.png

