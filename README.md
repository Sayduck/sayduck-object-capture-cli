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

| name              | entries | input                                                                                            | output                                                                                                   | source                                       | note              |
| ----------------- | ------- | ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------- | -------------------------------------------- | ----------------- |
| Gargoyle          | 23      | [![Input](Datasets/gargoyle/input.jpg \| height=150)](Datasets/gargoyle/input)                   | [![Output](Datasets/gargoyle/output.jpg \| height=150)](Datasets/gargoyle/output.usdz)                   | Nicky                                        | Very poor quality |
| Gnome             | 27      | [![Input](Datasets/gnome/input.jpg \| height=150)](Datasets/gnome/input)                         | [![Output](Datasets/gnome/output.jpg \| height=150)](Datasets/gnome/output.usdz)                         | [source](http://zhuoliang.me/meshrecon.html) |
| Teapot            | 26      | [![Input](Datasets/teapot/input.jpg \| height=150)](Datasets/teapot/input)                       | [![Output](Datasets/teapot/output.jpg \| height=150)](Datasets/teapot/output.usdz)                       | [source](http://zhuoliang.me/meshrecon.html) |
| Woodland Squirrel | 20      | [![Input](Datasets/woodland-squirrel/input.jpg \| height=150)](Datasets/woodland-squirrel/input) | [![Output](Datasets/woodland-squirrel/output.jpg \| height=150)](Datasets/woodland-squirrel/output.usdz) | [source](http://zhuoliang.me/meshrecon.html) |
