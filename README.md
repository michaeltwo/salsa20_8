# CS_HW1
XXXXX

## Instructions

Use the debain package manager apt to install python3 ( if python3 is not installed )

```bash
apt install python3
```

## Usage
#### Step 1, locate to the salsa20_8.py file folder, in the same folder simply run command as below. Otherwise, you can directly run python3 path/salsa20_8.py (replace your real path)

```python
$ python3 salsa20_8.py

# Output Results
Result (hex): 741f797da6c2b1e5bb1d9f7c72a3ee
Result contains non-printable characters, displaying as hex.
Result (text): 741f797da6c2b1e5bb1d9f7c72a3ee
```

## logging
nonce:1234567890abcdef  
key(128):deadbeefdeadbeefdeadbeefdeadbeef  
key(256):153eae538056c9486a6204446038ade85ad004dc9c78cba1fefd65e9e3bf0354  
key(64):7f3a9c6e15b8d24f  
input text:546869736973706c61696e74657874  


![128bit Test](128b.png)

![64bit Test](64b.png)

![256bit Test](256b.png)

![1KB Test](1kb.png)

## Salsa20_8

[mygithub_Source](https://github.com/michaeltwo/salsa20_8.git)
