This book is built using [Quarto](https://quarto.org/docs/books/)

Install Quarto:

```{r}
install.packages("quarto")
```

After editing a quarto file, commit the changes and then push to the repo - Github should automatically render the file. 

For example, you edit `03_atacseq_qc.qmd` - adding in text and figures. Then:

```{bash}
git add 03_atacseq_qc.qmd
git commit -m "I've edited x, y, z and added this figure." 
git push 
```

This will be enough to rebuild deploy the updated website. You do not need to render `03_atacseq_qc.qmd` to html and commit the html to the repo - do not do that. Just edit the `qmd` files and push those changes to the repo. If you have any problems, let Adele know.

The book is using a minimum amount of R packages - if you include something that requires an R package installed, let Adele know and she'll update the dependencies so that the book will deploy.

The quarto files are numbered according to the chapter progress in the book. If you think there should be a new section in between existing files, feel free to add a new file and then rename the rest accordingly. 

