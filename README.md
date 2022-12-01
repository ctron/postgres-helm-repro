See the issue using:


```sh
helm template . | grep -A 5 -B 5 security
```

One can see the `foo: bar` entries, but also the masked out (using `null`) entries. They should be gone.
