<div align="center">

# crait

The framework for app templates, using AI. Inspired by [Fireship](https://fireship.io).

`◽️ ~ pip install crait`

</div>

## Try

To learn how to create a simple integration with Crait and see how it works under the hood, use the `new` command to try it out:

```shell
$ crait new "simple crait integration"

> Framework:  Crait
> Docs:       Crait

✨ Generated in `simple_crait.py` (2.353s)
```

<details>
  <summary>simple_crait.py</summary>
  <p>

```python
from crait import Crait

if __name__ == "__main__": # create app cli
    crt = Crait(
        framework="FastAPI", # framework name
        docs="https://fastapi.tiangolo.com", # docs for AI's reference
    )
    crt.create(
        file="output.py",
        input="simple app" # or user input
    )
```

  </p>
</details>

<div align="center">
  
# Coming Soon.

</div>
