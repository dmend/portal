# Meniscus Portal
Moving data quickly

## Building Portal
```bash
pip install -r tools/pip-requires
pip install -r tools/test-requires
python setup.py build_ext --inplace
nosetests
```

## Example Server
[Portal Server Example using libev](https://github.com/ProjectMeniscus/portal/blob/master/portal/server.py)
