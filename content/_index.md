+++
title = "Revelation Hello World"
outputs = ["Reveal"]
+++

## Hello world

This is my first slide

---

## Hard coded slide

```python
def main():
    print("hello world")

for x in range(1):
    print(x)
```

---

## Sync slide

``````markdown
```python
{{%/* snippet "# hello" */%}}
```
``````

```python
{{% snippet "# hello" %}}
```

---

## directory structure

```txt
content
├── code
│   └── main.py
└── _index.md
```