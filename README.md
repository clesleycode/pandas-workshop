## Environment Setup

In this tutorial, we'll be using Python to show how different statistical concepts can be applied computationally. Specifically, we'll be working with numpy, a scientific computing module in Python.

This guide was written in Python 3.6. If you haven't already, download [Python](https://www.python.org/downloads/release/python-361/) and [Pip](https://pypi.python.org/pypi/pip). Next, you’ll need to install the numpy module that we’ll use throughout this tutorial:

```
pip3 install pandas==0.20.3
pip3 install jupyter==1.0.0
```

Since we’ll be working with Python interactively, using the Jupyter Notebook is the best way to get the most out of this tutorial. You already installed it with pip3 up above, now you just need to get it running. With that said, open up your terminal or command prompt and entire the following command: 

```
jupyter notebook
```

And BOOM! It should have opened up in your default browser. Now we’re ready to go. 

### A Quick Note on Jupyter

For those of you who are unfamiliar with Jupyter notebooks, I’ve provided a brief review of which functions will be particularly useful to move along with this tutorial. 

In the image below, you’ll see three buttons labeled 1-3 that will be important for you to get a grasp of -- the save button (1), add cell button (2), and run cell button (3). 

![alt text](https://www.twilio.com/blog/wp-content/uploads/2017/10/XCdsHFjl8mmg1BT55TZorU8dcUx-DsTlxGZJmeqQMbXk3vv0lPJ-O8YIHjSPwxZ8M2Nw1vOcByUHM_lIRuIpKQ6LASxtcnjyHpf1UpSRKbY0qF1bEgA_hzfRu1pX7y8cSXPgZPEG.png)

The first button is the button you’ll use to save your work as you go along (1). I won’t give you directions as when you should do this -- that’s up to you! 
Next, we have the “add cell” button (2). Cells are blocks of code that you can run together. These are the building blocks of jupyter notebook because it provides the option of running code incrementally without having to to run all your code at once.  Throughout this tutorial, you’ll see lines of code blocked off -- each one should correspond to a cell. 

Lastly, there’s the “run cell” button (3). Jupyter Notebook doesn’t automatically run your code for you; you have to tell it when by clicking this button. As with add button, once you’ve written each block of code in this tutorial onto your cell, you should then run it to see the output (if any). If any output is expected, note that it will also be shown in this tutorial so you know what to expect. Make sure to run your code as you go along because many blocks of code in this tutorial rely on previous cells. 
