---
authors:
  - name: Calvin Rans

kernelspec:
  name: python3
  display_name: 'Python 3'
---

# Preface

## Testing
I am trying to figure out how relative paths work as I am having trouble with paths when building my book locally and in github.

*./Figures/test_image.svg*

```{figure} ./Figures/test_image.svg
:alt: Test image 
:width: 400px
:align: center
```

*/Figures/test_image.svg*

```{figure} /Figures/test_image.svg
:alt: Test image 
:width: 400px
:align: center
```

*Figures/test_image.svg*

```{figure} Figures/test_image.svg
:alt: Test image 
:width: 400px
:align: center
```