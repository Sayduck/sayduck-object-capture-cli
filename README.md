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
| gargoyle          | 23      | [![Input](Datasets/gargoyle/input.jpg)](Datasets/gargoyle/input)                   | [![Output](Datasets/gargoyle/output.png)](Datasets/gargoyle/output.usdz)                   | Nicky                                        | Very poor quality |
| gnome             | 27      | [![Input](Datasets/gnome/input.jpg)](Datasets/gnome/input)                         | [![Output](Datasets/gnome/output.png)](Datasets/gnome/output.usdz)                         | [source](http://zhuoliang.me/meshrecon.html) |
| squirrel          | 23      | [![Input](Datasets/squirrel/input.jpg)](Datasets/squirrel/input)                   | [![Output](Datasets/squirrel/output.png)](Datasets/squirrel/output.usdz)                   | [source](http://zhuoliang.me/meshrecon.html) |
| teapot            | 26      | [![Input](Datasets/teapot/input.jpg)](Datasets/teapot/input)                       | [![Output](Datasets/teapot/output.png)](Datasets/teapot/output.usdz)                       | [source](http://zhuoliang.me/meshrecon.html) |
| woodland-squirrel | 20      | [![Input](Datasets/woodland-squirrel/input.jpg)](Datasets/woodland-squirrel/input) | [![Output](Datasets/woodland-squirrel/output.png)](Datasets/woodland-squirrel/output.usdz) | [source](http://zhuoliang.me/meshrecon.html) |
| zound             | 20      | [![Input](Datasets/zound/input.jpg)](Datasets/zound/input)                         | [![Output](Datasets/zound/output.png)](Datasets/zound/output.usdz)                         | Greg                                         |
