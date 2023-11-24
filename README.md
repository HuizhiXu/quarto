# Display Jupyter Notebook or Qmd with Quarto

## 1. Install 
install the quarto extension in VSCode

### 2. Usage
#### Jupyter Notebook
```python
quarto preview gaussian_process.ipynb
```



#### Qmd File (To html/docx)
```python
quarto render uncertainty.qmd --to html
quarto render uncertainty.qmd --to docx
```

### 3. Display
The generated files are in the same folder as the qmd file.
The html file can be displayed in the browser. The docx file can be opened in Word.