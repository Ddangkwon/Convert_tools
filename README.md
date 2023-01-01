# fileconvtools

## csv to xlsx convert

*.csv 확장자 파일을 *.xlsx 파일로 변환합니다.
## Installation

```bash
pip install fileconvtools
```

```bash
pip install --upgrade fileconvtools==0.0.4
```

## Quick start
```python
>>> from fileconvtools.main import csv_to_xlsx
>>> csv_to_xlsx()
```



## 배포절차

python setup.py sdist bdist_wheel
pip install twine

pip install --upgrade fileconvtools==0.0.4

파일 빌드
- python setup.py sdist bdist_wheel


Pypi 상에 배포
- python -m twine upload dist/*


