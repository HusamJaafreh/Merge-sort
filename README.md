# Merge Sort

A recursive implementation of the merge sort algorithm in Python.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## How it works

1. **Divide:** split the list in half recursively until each piece has one element.
2. **Conquer:** merge the sorted halves back together by repeatedly taking the smaller front element.

| Case    | Time       | Space |
|---------|------------|-------|
| Best    | O(n log n) | O(n)  |
| Average | O(n log n) | O(n)  |
| Worst   | O(n log n) | O(n)  |

Merge sort is **stable** and has guaranteed O(n log n) performance, which makes it a good choice for linked lists and external sorting.

## Run it

```bash
jupyter notebook "merge sort.ipynb"
```

No third-party dependencies are needed.

## License

[MIT](LICENSE)
