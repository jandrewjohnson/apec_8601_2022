# apec_8601_2022
Code for APEC 8601: Natural Resource Economics

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jandrewjohnson/apec_8601_2022/HEAD)

Once inside, open up the file fisheries_notebook.ipynb to get started.

If you want to run this locally (and assuming you have Docker installed), run the following command in this folder:

    docker run -it -p 8888:8888 -v /c/files/repositories/apec_8601_2022_code/apec_8601_2022/:/notebooks/. apec_8601_2022

If you need to build the docker image first, run:
    
    docker build --tag apec_8601_2022 .

Or if you want a complete rebuild:

    docker build --no-cache --tag apec_8601_2022 .