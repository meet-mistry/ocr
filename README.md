# Usage
```shell
python main.py -i <input_path> -o <output_path>
```

```
usage: main.py [-h] -i INPUT [-o OUTPUT] [-d]

required arguments:
  -i INPUT, --input INPUT       Single image file path or images directory path

optional arguments:
  -o OUTPUT, --output OUTPUT    (Optional) Output directory for converted text
  -d, --debug                   Enable verbose DEBUG logging
```

```shell
python main.py -i sample/
```

OR

```shell
python main.py -i sample/ -o output/
```

## Run Test
```
python -m unittest
```