# LiteRadar

This version is a fork of [LiteRadar]() which is a child of [LibRadar](). It is used to detect third-party libraries inside Android APKs. The fork is meant to work specifically with our AndroidCrypto project, so far private one. 

## Changelog

In difference to original version of LiteRadar, our provides two tiny changes:

1. The tool takes two arguments and stores the results in the file provides as a second argument.
2. Deleting of temporary files is allowed so no traces are left behind.


## Usage

1. (Optionally) Download the newest version of the feature vector from [Github mirror](https://github.com/pkumza/Data_for_LibRadar/blob/master/lite_dataset_10.csv) and place it to `./LiteRadar/Data` folder.
2. Run

```bash
$ python literadar.py <someapp.apk> </path/to/where/to/store/result.json>
```

View [docs/QuickStart.md](https://github.com/pkumza/LiteRadar/blob/master/docs/QuickStart.md) for more information.