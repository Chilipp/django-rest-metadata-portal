# django-rest-metadata-portal
Quick and dirty example how to generate a metadata RestAPI from Django

This presentation is part of the (virtual) HGF MareHUB Raster Metadata workshop
on October 15th, 2020.


Open the [PDF-](django-rest-metadata-demo.pdf) or
[HTML](django-rest-metadata-demo.html)-file for a compiled version of the
[presentation (notebook)](django-rest-metadata-demo.ipynb).

## Requirements to run this notebook

- `linux` or `osx`
- `django`
- `djangorestframework`, for the rest api
- `uritemplate`, for generating an openAPI schema

and for generating a graph of the database_
- `graphviz`
- `django-extensions`

Install everything via:

```bash
conda create -n django-metadata -c conda-forge django-extensions graphviz uritemplate djangorestframework
```
