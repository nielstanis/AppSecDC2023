# Python on WASM / WASI

```python
import platform
platform.platform()
f = open("/etc/hosts", "r")
print(f.read())
```

## WasmTime
- `wasmtime run python.wasm --dir=. demo.py`
- `wasmtime run python.wasm --dir=/etc --dir=. demo.py`