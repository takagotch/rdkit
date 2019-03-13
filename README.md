### rdkit
---
https://github.com/rdkit/rdkit

http://www.rdkit.org/docs/GettingStartedInPython.html

```py
from __future__ import print_function
from rdkit import Chem

m = Chem.MolFromSmiles('Cc1ccccc1')
m = Chem.MolFromMolFile('data/input.mol')
stringWithMolData=open('data/input.mol', 'r').read()
m = Chem.MolFromMolBlock(stringWithMolData)

m = Chem.MolFromFile('data/invalid.mol')
m is None
```

```
```

```
```


