# 2025-02-04-dockerfile

Hello from inside the container.
```
docker run --rm -it -e PASSWORD="password" -p 8787:8787 -v /$(pwd):/home/rstudio/work rocker/tidyverse:4.4.2
```

