
## Getting Started

```
brew install pipenv
pipenv install
```


## Make Project Directory

```
PIPENV_VENV_IN_PROJECT=true pipenv install
```

## Deploy
```
$ pipenv lock -r > requirements.txt
$ gcloud functions deploy main --runtime python37 --trigger-http
```

## Run

```
$ gcloud functions call main --data {}
```

## References

