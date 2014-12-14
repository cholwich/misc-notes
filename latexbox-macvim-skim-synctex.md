LaTeX-Box + MacVim + Skim + SyncTeX
===================================

## Setting
Use synctex option when a LaTeX is compiled in .latexmkrc:
```
$pdf_mode = 1;
$pdflatex = 'pdflatex -synctex=1 --interaction=nonstopmode';
```
Use LaTeX-Box bundle in MacVim (.vimrc)
```
Bundle 'LaTeX-Box-Team/LaTeX-Box'
```
Use Skim as a PDF viewer (.vimrc)
```
let g:LatexBox_viewer = "open -a Skim"
```
## Usage
- Use `\ll` to compile a LaTeX file.
- Use `\lv` to view the obtained PDF file.
- Use Cmd+Shift+LeftClick to do a backward search.
