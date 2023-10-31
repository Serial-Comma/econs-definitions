# econs-definitions
lmao


funny code cause i forgot the bold the things
```python
html = """

insert html here

"""

html = html.split("\n")
lst = []
for i in range(len(html)):
    if html[i][0:3] == "<p>":
        h = html[i]
        h = h.split(":")
        h[0] = f"<b>{h[0][3:]}:</b>"

        string = ''
        
        
        string = (f"<p>{h[0]}{h[1]}")
    else:
        string = html[i]
    print(string)

```
