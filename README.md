# [blog]()
A repo to blog about summer development on Project Jupyter at Cal Poly.

## Description

This blog uses the [Nikola](https://getnikola.com/) project to build a static
website. Among other things, Nikola provides support for notebooks.

## Developer install

1. Fork and clone the repo.
2. Change directory to blog `cd blog`
3. Create a conda environment
   ```
   conda env create -f environment.yml
   ```

4. Activate the conda environment
   ```
   source activate blognikola
   ```
   
To build the blog:
```
python3 -m nikola build
```

To serve the blog locally:
```
python3 -m nikola serve
```

## Development tips

To clean up any cruft before building the blog:
```
python3 -m nikola clean
```

## Deploying the blog to GitHub pages
