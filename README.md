# Developing a Rudimentary Blockchain with Streamlit

Blockchain is a technology that is poised to disrupt multiple industries. In this application, we explore developing a rudimentary blockchain that holds transaction data, paticularly the sender and receiver ID along with the amount. We then use the Streamlit library to show the growing blockchain through a front end website. 

---

## Technologies 

This application was built on Python 3.7. Streamlit library enables the blockchain to have a front end visual for users. 

To run this code, in terminal run: 

`streamlit run pychain.py`

---

## Libraries

Import statements already present in program, refer to them below:

```python
import streamlit as st
from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib
```

---

## Results

The following is an example of the resulting blockchain with a few blocks: 



The following is an example of the validate blockchain feature returning that the blockchain is a valid one:




---
## Contributors

Thank you for Eric Cardena for teaching Rice's FinTech Boot Camp. He was instrumental in teaching and helping us understand this material. Thank you for Rice for preparing this curriculum and the corresponding data sets that are required to be used. 

**Rishi Prasadha**

**LinkedIn**: https://www.linkedin.com/in/rishi-prasadha-912212133/

**Instagram**: @therishiprasadha

**Twitter**: @RishiPrasadha

---

## Licenses 

MIT
