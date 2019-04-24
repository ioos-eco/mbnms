# mbnms
Monterey Bay National Marine Sanctuary infographics

## Develop

Because of CORS, need local web server to debug:

```r
setwd(here::here("docs"))
servr::httw()
```

or

```bash
python -m SimpleHTTPServer 8000
```