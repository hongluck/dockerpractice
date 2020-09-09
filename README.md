# dockerpractice

```docker pull waleedka/modern-deep-learning```

### Running docker image

`docker run -it -p 8888:8888 -p 6006:6006 -v ~/:/host waleedka/modern-deep-learning`

### Running Jupyter Notebook
```
cd /host    # So Jupyter Notebook uses this as it's root
jupyter notebook --allow-root
http://0.0.0.0:8888/


```

