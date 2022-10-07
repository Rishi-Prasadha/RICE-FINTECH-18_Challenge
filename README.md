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

<img width="1535" alt="Screen Shot 2022-10-07 at 16 51 24" src="https://user-images.githubusercontent.com/107497500/194669345-9a9a3c09-8bba-45fc-ba08-7180fcffed27.png">


The following is an example of the validate blockchain feature returning that the blockchain is a valid one:

<img width="1536" alt="Screen Shot 2022-10-07 at 16 53 57" src="https://user-images.githubusercontent.com/107497500/194669351-8a735f20-b9ad-49a2-ad3f-3c48927efdeb.png">



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
