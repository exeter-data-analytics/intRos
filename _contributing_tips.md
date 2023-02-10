## Contributing to this repository

This is a set of rules to follow for contributing to this repository. To re-render this set of tips as a pdf, run `pandoc --pdf-engine=xelatex -V papersize:a4 -V geometry:"top=2cm, bottom=1.5cm, left=2cm, right=2cm" _contributing_tips.md -o contributing_tips.pdf` in the Terminal.

1. run `git pull`. The easiest way to to do this is using the **Pull** button from the RStudio Git pane.

2. when creating a new post, create a new folder for the post inside the `posts` directory. Then copy the post template into that folder using Terminal `cp _post_template.qmd posts/new_folder_name/indez.qmd`. Then edit that new file to create the new walkthrough

3. re render the website using the **Render Website** button from the RStudio Build pane. Alternatively you can use the Terminal and run `quarto render`.

4. re render individual files using Terminal `quarto render path/to/single/file`

5. commit and push changes. The easiest way to do this is in the RStudio Git pane using the **commit** and **Push** buttons.