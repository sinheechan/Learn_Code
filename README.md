# Learn_Code


## 1. Setting

<br/>

### Import List

```python

# Basic Setting

import numpy as np 
import pandas as pd
import seaborn as sns 
import matplotlib.pyplot as plt
%matplotlib inline

import warnings
warnings.filterwarnings('ignore')
```
<br/>

```python

# plt & sns Setting

sns.set_theme(context='notebook',
              style='whitegrid',
              palette='rainbow',
              font='Lucida Calligraphy',
              font_scale=1.5,
              rc=None)
matplotlib.rcParams['figure.figsize'] = [8, 8]
matplotlib.rcParams.update({'font.size': 15})
matplotlib.rcParams['font.family'] = 'sans-serif'

```

<br/>

## 2. Data Loading

<br/>

```python

# CSV
pd.read_csv(File)

# Excel
pd.read_excel(File) # 구
pd.read_excel(File, engine='openpyxl') # 신

# Json
pd.read_json('File')

# txt
with open('file.txt', 'r') as f:
    data = f.read()
print(data)

```

<br/>

### Data EDA

```python
df = pd.read_csv("")



# 기본 통계량
df.describe()

# 결측치 확인
df.isnull().sum()

# 유니크한 값 개수 확인
df['category_column'].unique()

# 빈도수 확인
df['category_column'].value_counts()



```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```
<br/>

```python

```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```

<br/>

```python

```
