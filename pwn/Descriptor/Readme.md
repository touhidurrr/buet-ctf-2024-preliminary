### Challenge Name: Descriptor

### Challenge Category: PWN

### Challenge Level: Easy

### Challenge Author: marufmurtuza

### Challenge Flag

``BUETCTF{L34k3d_F1L3_Thr0ugh_Pyj41l_3xpl01t_F1l3_D3scr1pt0r_M4g1c}``

### Challenge Description

Escape the jail!

- [Artifact](./challenge.py)

### Solution

- `nc <host> <port>` -> `print(read(open('flag.txt', os.O_RDONLY), 100))`

