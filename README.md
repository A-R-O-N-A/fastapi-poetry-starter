# FastAPI - Poetry Starter kit

+ This projecty was initialized using `poetry init`.

+ `fastapi` was then initially installed as the initial dependency.

## Installing dependencies after cloning this repo

Install the packages and create `virtual environment` with the following command :

```sh
poetry install --no-root
```

_check if a virtual environment has been installed_
```sh
poetry env list

# double check the `site-packages` by inspecting the actual cache file

poetry env infor --path

# if its there complete, proceed to activate
# if not, just run poetry install --no-root
```

_using powershell_
```sh
Invoke-Expression (poetry env activate)
```

after this you should see the env name in your terminal, you can then run your python project

## Running FastAPI
After running the above and activating your poetry env, you can now run : 

```sh
fastapi dev main.py
```



