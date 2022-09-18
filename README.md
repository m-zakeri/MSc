# MSc
My M.Sc. thesis preprint


## How to run?

1. `git clone https://github.com/m-zakeri/MSc.git`
2. `xelatex.exe -synctex=1 -interaction=nonstopmode "_main_".tex`
3. `xindy -L persian-variant1 -C utf8 -I xindy -M "_main_".xdy -t "_main_".glg -o "_main_".gls "_main_".glo`
4. `xelatex.exe -synctex=1 -interaction=nonstopmode "_main_".tex`

