# Performance benchmark for RAM (RDF ADT Mapping)

This is a performance benchmark for [ram-shapes](https://github.com/AlexeyMz/ram-shapes) library.

## Installation
1. Run `npm install` to install dependencies.
2. *(Optional)* Execute `npm link` in the checked out copy of the ram-shapes library and `npm link ram-shapes` to benchmark the latest library version.
3. Run `npm run build` to compile the code.

## Usage
After executing installation steps, run one of the following entry points:

| Entry point               | Description                                    |
|---------------------------|------------------------------------------------|
| `dist/fetch-manifests.js` | Fetches IIIF manifests into `datasets/iiif`    |
| `dist/annotation.js`      | Runs simple benchmark on OA annotation data    |
| `dist/iiif.js`            | Runs full benchmark on IIIF manifest data      |
| `dist/latex.js`           | Prepares benchmark stats as latex chart data   |
| `dist/comparison.js`      | Generates library comparison on simple example |

After running `dist/iiif.js` you can manually inspect frame and flatten operation results for each test case.

## References
A publication which describes this work is currently under review at 
Semantics-2019 conference.
