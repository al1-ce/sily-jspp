# Sily Lib for JS++

# Archived since I do not intend to work on it anymore (at least for now). See jsppext for more detail

## Contents
- sily.assets: Everything related to asset-type resources. Including Images, Audio, Fonts, etc
- sily.engine: Basic game engine
- sily.std: Global-scope modules, like Math, Conv, String
- sily.web: All browser & DOM related

## Getting js++ v.0.10.0 compliant code
1. Clone lib into any folder folder.
2. Open terminal and go into that directory.
3. Use [jsppext](https://github.com/al1-ce/jspp-compiler-extension) to preprocess with command `jsppext -b jsppext2jspp` or just `jsppext -b`.
4. js++ compiler compliant code will be in `____jspp_temp` directory.
