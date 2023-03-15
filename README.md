# pyconkr-api-v2

파이콘 한국 행사를 위한 API 서비스입니다. (2023 ~ )

## Prerequisites

- Python 3.x+

## 기여하기

```shell
git clone https://github.com/pythonkr/pyconkr-api-v2.git
cd pyconkr-api-v2
```

## PR 이전에

- 컨벤션 유지를 위해 `black`과 `isort`를 적용하고 있습니다.

## 개발 환경

- mysql-client 설치
  - mac
    - brew install mysql-client
- pip install -r requirements.txt

## how to run localtesting ( sqlite3 based )

```shell
# to setup pytest and requirements
pip install -r requirements-dev.txt
# run test
pytest
```
