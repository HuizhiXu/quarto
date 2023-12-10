# Display Jupyter Notebook or Qmd with Quarto

## 1. Install 
install the quarto extension in VSCode

### 2. Usage
#### Jupyter Notebook
```python
quarto preview gaussian_process.ipynb
```

jupyter notebook 转为qmd
```
quarto convert gaussian_process_in_practice.ipynb
```


#### Qmd File (To html/docx)
```python
quarto render uncertainty.qmd --to html
quarto render uncertainty.qmd --to docx
```




### 3. Display
The generated files are in the same folder as the qmd file.
The html file can be displayed in the browser. The docx file can be opened in Word.


### 4. Qmd grammer
- add image
```
![1.png](1.jpg){width="80%" fig-align="right"}
```


- md格式的 math equation的加粗是\bold，在qmd里面是 \boldsymbol