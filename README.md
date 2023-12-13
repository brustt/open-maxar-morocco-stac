# open-maxar-morocco-stac
Reader for stac items from open-maxar STAC catalog (aws) - Marocco Earthquake.

Catalog STAC : 
https://stacindex.org/catalogs/maxar-open-data-catalog-ard-format#/SBGqmoqQQwHLHF4WWhHjX7Y4ZzG9YtfcPBqu43eMhNYagC8cvmeHQnKoR2tV?t=1

Please create output directory before run (see notebook `out_dir_path`).


#### Installation requirements

* Create environment conda from environment.yml
```
conda create -f environment.yml
```
* Activate env :
```
conda activate eo
```
Then run the code on whatever you like : jupyter notebook, jupyter lab etc

I recommend to use mamba as package manager than conda. It's faster, fully compatible with conda (same commands) and the name is so cool.


#### References
Code based on leafmap and eodag.
* leafmap source code : https://github.com/opengeos/leafmap/blob/master/leafmap/stac.py
* eodag source code : https://github.com/CS-SI/eodag

#### Python version
python 3.10

