# odm

run ODM
```
docker run -it --rm \
    -v "$(pwd)/images:/code/images" \
    -v "$(pwd)/odm_orthophoto:/code/odm_orthophoto" \
    -v "$(pwd)/odm_texturing:/code/odm_texturing" \
    opendronemap/opendronemap
```