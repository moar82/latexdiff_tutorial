# latexdiff tutorial

Example:

For a simple example, suppose version 1 of our LaTeX document is the following: 
![Screenshot](version1.png)

We notice a few errors, so we fix them in version 2 below: 
![Screenshot](version2.png)

If we want to easily see the differences between the two versions, latexdiff will produce the following: 
![Screenshot](diff.png)


## Instructions:
1. Install latexdiff 

for example: ``` sudo dnf install -y texlive-latexdiff ``` (Fedora)

2. Clone this repository
3. Run the following command:

    ```latexdiff version1.tex version2.tex > diff2.tex```
    
4. Compile the resulting diff2.tex 
    
    for example: ``` pdflatex diff2.tex ```
    
4. Open the output pdf file with your favorite pdf viewer

    for example: ```evince diff2.pdf```




## References

[1. Using overleaf and latexdiff](https://www.overleaf.com/learn/latex/Articles/Using_Latexdiff_For_Marking_Changes_To_Tex_Documents)

[2. git and latexdiff](http://www.deanbodenham.com/learn/git-and-latexdiff.html)

[3. How to calculate circumference of a circle, if you forgot how to](https://www.wikihow.com/Calculate-the-Circumference-of-a-Circle)

[4. To ignore certain environments in case of errors](https://tex.stackexchange.com/questions/73224/is-there-an-option-in-latexdiff-to-ignore-whole-environments)

[5. Main latexdiff CTAN's site](https://ctan.org/tex-archive/support/latexdiff)
