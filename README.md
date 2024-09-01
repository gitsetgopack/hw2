# hw2
Second SE homework on Debugging

---

![pylint]()

---
### Steps
1. Install python requirements
   ```bash
   pip install -r requirements.txt
   ```
2. Running autopep8 on all files
    ```bash
    autopep8 -i src/*
    ```
3. Running pylint
   ```bash
   pylint src/* >> src/post_traces/pylint.txt # first time
   pylint src/* # iteratively
   ```
4. Running pyright
   ```bash
   pyright src/* >> src/post_traces/pyright.txt # first time
   pyright src/* # iteratively
   ```
5. Running pytest
   ```bash
   pytest
   ```