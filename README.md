# Sayduck Photogrammetry

Sayduck's photogrametry proof of concept

## Run

How to compile the cli:

1. Launch the project in xcode
2. Archive the project
3. Drag Products -> SayduckPhotogrammetry to terminal window to get the compiled cli path
4. USAGE: hello-photogrammetry <input-folder> <output-filename> [--detail <detail>] [--sample-ordering <sample-ordering>] [--feature-sensitivity <feature-sensitivity>]

## Datasets

- Click on the input picture to open the input folder
- Click on the output picture to download the USDZ

| name              | entries | input                                                                              | output                                                                                     | source                                       | note              |
| ----------------- | ------- | ---------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | -------------------------------------------- | ----------------- |
| Gargoyle          | 23      | [![Input](Datasets/gargoyle/input.jpg)](Datasets/gargoyle/input)                   | [![Output](Datasets/gargoyle/output.jpg)](Datasets/gargoyle/output.usdz)                   | Nicky                                        | Very poor quality |
| Gnome             | 27      | [![Input](Datasets/gnome/input.jpg)](Datasets/gnome/input)                         | [![Output](Datasets/gnome/output.jpg)](Datasets/gnome/output.usdz)                         | [source](http://zhuoliang.me/meshrecon.html) |
| Squirrel          | 23      | [![Input](Datasets/squirrel/input.jpg)](Datasets/squirrel/input)                   | [![Output](Datasets/squirrel/output.jpg)](Datasets/squirrel/output.usdz)                   | [source](http://zhuoliang.me/meshrecon.html) |
| Teapot            | 26      | [![Input](Datasets/teapot/input.jpg)](Datasets/teapot/input)                       | [![Output](Datasets/teapot/output.jpg)](Datasets/teapot/output.usdz)                       | [source](http://zhuoliang.me/meshrecon.html) |
| Woodland Squirrel | 20      | [![Input](Datasets/woodland-squirrel/input.jpg)](Datasets/woodland-squirrel/input) | [![Output](Datasets/woodland-squirrel/output.jpg)](Datasets/woodland-squirrel/output.usdz) | [source](http://zhuoliang.me/meshrecon.html) |
