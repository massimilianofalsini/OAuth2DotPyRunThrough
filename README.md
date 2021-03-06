# OAuth2DotPyRunThrough

> This is the [OAuth2DotPyRunThrough](https://github.com/google/gmail-oauth2-tools/wiki/OAuth2DotPyRunThrough) updated to python 3 and it is a web server instead of a cli.

## Requirements & Dependencies

You need python 3.10 or higher.

To install all dependencies on the root of the project type.

```bash
make dep
```

## Configuration

Inside main.py add your CLIENT_ID and CLIENT_SECRET

```python
CLIENT_ID: str = ''
CLIENT_SECRET: str = ''
```

## Run

To run the web server on the root of the project type.

```bash
make
```

or

```bash
make run
```

## Install dependencies and run

To install all dependencies and run on the root of the project type.

```bash
make run_new
```
