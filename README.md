# Nextstrain Instance: the transmission of Delta variant in the greater Houston area

<!-- TODO: update links -->

Use Git to download a copy of the ncov repository containing the workflow.

```shell
git clone https://github.com/nextstrain/ncov.git
```

Change directory to the ncov directory:

```shell
cd ncov
```
Replace the lat_longs.tsv:

Download this repository into a new subdirectory of ncov/ called deltaInGreaterHoustonArea/:

```shell
git clone https://github.com/leke-lyu/deltaInGreaterHoustonArea.git
```

```shell
rm defaults/lat_longs.tsv
cp deltaInGreaterHoustonArea/lat_longs.tsv defaults/
```

From within the ncov/ directory, run the workflow using a configuration file provided in the tutorial directory:

```shell
nextstrain build . --configfile deltaInGreaterHoustonArea/builds.yaml 
```
