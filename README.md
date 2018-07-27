# dictfilter

## installation

```shell
pip install dictfilter
```

## usage

```python
bsg = {
    'class': 'Battlestar',
    'model': 'Jupiter',
    'name': 'Galactica',
    'crew': {
        'commander': 'William Adama',
        'xo': 'Saul Tigh',
        'cag': 'Kara Thrace',
    }
}

result = query(some_data, ['class', 'name', 'crew.captain'])

# {
#     'class': 'Battlestar',
#     'name': 'Galactica',
#     'crew': {
#         'commander': 'William Adama',
#     }
# }
```
