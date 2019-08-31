This is the Chinese translation source code underlying the post [Common statistical tests are linear models (or: how to teach stats)](https://lindeloev.github.io/tests-as-linear/). The original post's author explained it in [this Twitter thread](https://twitter.com/jonaslindeloev/status/1110907133833502721).

This is the main content:

 * **index.Rmd** is the Rmarkdown code which generated the post.
 * **linear_tests_cheat_sheet.html** is a HTML file with the cheat sheet. (The pdf is generated using Chrome "print to pdf", the png is generated [by using `gs`](https://superuser.com/questions/49099/) by running `gs -dBATCH -dNOPAUSE -sDEVICE=png16m -dGraphicsAlphaBits=4 -dTextAlphaBits=4 -r200 -sOutputFile=linear_tests_cheat_sheet.png linear_tests_cheat_sheet.pdf`)
 * **simulations** folder are the simulations of the accuracy of the parametric approximation to non-parametric tests.
 
Please contribute! For example:

* Raise issues if you have ideas.
* Submit pull requests if you want to participate improving it.
* Star it if you just want to follow updates
* Fork it to make your own spin!