[TOC] 

# Create .gitignore for large files
```python
import os
path = "."

cmd = 'find ' +path + ' -size +50M | cat >> .gitignore'
os.system(cmd)
with open('.gitignore', 'r') as f:
    lines = f.read().splitlines()
    lines = [line.replace('./', '') for line in lines]
with open('.gitignore', 'w') as f:
    f.write('\n'.join(lines))
os.system('cat .gitignore')
```

# Assign GPU
```python
os.environ['CUDA_VISIBLE_DEVICES'] = '0'
device_name = tf.test.gpu_device_name()
with tf.device(device_name):
```
