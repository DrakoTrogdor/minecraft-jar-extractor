# minecraft-jar-extractor
[![NPM version](https://img.shields.io/npm/v/minecraft-jar-extractor.svg)](http://npmjs.com/package/minecraft-jar-extractor)

Extract structured data from the minecraft jar

## image name extractor

Just run `node image_names.js <version1,version2,...> <output_dir> <temporary_dir>` and get a directory containing the name->texture mapping and the textures.

Result of that currently online at [minecraft-assets](https://github.com/rom1504/minecraft-assets)

## protocol extractor

How to use it:

1. `node downloadDecompile.js 1.8.8 /tmp/the_output`
2. `node protocol_extractor.js /tmp/the_output/decompiled`
3. get a protocol.json describing the classname<->id relation and some fields information

## History

### 0.0.0

* imported from minecraft-data + description added