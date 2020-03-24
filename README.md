Docker container for running [Folding@Home](http://folding.stanford.edu/)

### Usage
```bash
docker run --rm -it -p7396:7396 vmtoclud/folding-at-home:latest \ 
--user=VMtoCloud --team=52737 --gpu=false --smp=true --power=full
```

The web console is available on port `7396`.
