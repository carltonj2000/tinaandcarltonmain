# Tina And Carlton

Main Landing page for
[Tina and Carlton](http://tinaandcarlton.com).

## Digital Ocean Setup And Release Procedure

Steps below done in the DO `/mnt/volume_sfo2_02/cj/tinaandcarlton` directory.

### Digital Ocean Setup

- `git clone https://github.com/carltonj2000/tinaandcarltonmain.git`;
- `ln -s tinaandcarltonmain\main main`
- `ln -s <picture path> main\picture.[jpeg|jpg|png]`

### Digital Ocean Release Procedure

For every trip:

- A week before the trip edit `index.html` to redirect to the
  `<trip directory>`.
- About a month after trip edit `index.html` to redirect to the `main`
  directory.
- `ln -s <trip picture> main\picture.[jpeg|jpg|png]`.
