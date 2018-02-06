# graphics.py
http://mcsp.wartburg.edu/zelle/python/graphics.py

http://mcsp.wartburg.edu/zelle/python/graphics/graphics.pdf

# Install remotely
pip install https://raw.githubusercontent.com/jminz/graphics.py/master/graphics-py_installer.tar.gz

# Install manually
git clone https://github.com/jminz/graphics.py.git

tar -czvf graphics-py_installer.tar.gz ./graphics.py ./setup.py

pip install graphics-py_installer.tar.gz

# Quick Start
```python
from graphics import *

def main():
    win = GraphWin("My Circle", 600, 600)
    c = Circle(Point(50,50), 10)
    c.draw(win)
    win.getMouse() # Pause to view result, otherwise the window will disappear
    win.close()
main()
```

# Enjoy!
