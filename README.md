# Tina And Carlton

Main Landing page for
[Tina and Carlton](http://tinaandcarlton.com).

## Digital Ocean Setup And Release Procedure

Steps below done in the DO `/mnt/volume_sfo2_02/cj/tinaandcarlton` directory.

### Digital Ocean Setup

```bash
git clone https://github.com/carltonj2000/tinaandcarltonmain.git
# edit file and make changes for new additions.
# Links below should be
ln -s tinaandcarltonmain\main
ln -s tinaandcarltonmain\index.html 
cp <some_image.jpg> img/picture.jpg # for background image have been copying it
```

### Digital Ocean Release Procedure

For every trip:

- A week before the trip edit `index.html` to redirect to the
  `<trip directory>`.
- About a month after trip edit `index.html` to redirect to the `main`
  directory.
- `ln <trip picture> main\picture.[jpeg|jpg|png]`.

Note the symbolic link for the picture failed hence the hard link.

For wedding used the following picture path (deprecated).
`ln /mnt/volume_sfo2_02/cj_pics/pics2018/wedding/weddingDayPhotographer/carltontina-photo-download-part1of1/highlights/resized/size_1620x1080/untitled\(160of170\).jpg picture.jpg`

## History

### Hamburger Menu And Overlay With CSS on 2020-06-08

The code is based on the
[Pure CSS Hamburger Menu & Overlay](https://www.youtube.com/watch?v=DZg6UfS5zYg)
video.
