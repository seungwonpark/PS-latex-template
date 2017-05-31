# PS-latex-template

- LaTeX template for PS description.

# How to use

- Place IO data files to `input/`, `output/`.
	- File name format : `input%d.txt`, `output%d.txt` (Without leading zeros)
- Then `\iodataNo{%d}` will automatically parse txt files, show them in pdf file.
	- Tip : You may use `\foreach` loop as...
	```
	\foreach \i in {1, 2, ..., 15}{
		\iodataNo{\i}
	}
	```

# Notes

## For teachers
- Since I'm not professional at PS, feel free to discuss about any further utilites/issues at [Issues](https://github.com/seungwonpark/PS-latex-template/issues).

## For students

- I recommend to use [Foxit PDF Reader](https://www.foxitsoftware.com/products/pdf-reader). Then, you can : 
	- copy & paste the data from pdf file properly
	- directly view IO data files by clicking `입력1', `출력1` (Windows only).

# License

CC BY-NC-SA 3.0
