* [ ] Geocoding
    * [ ] Requirements:
        * [ ] rm googlemaps
        * [ ] add geocoder=1.38.1
        * [ ] add version for requests
    * [ ] New API key
    * [ ] Script for location parsing
    * [ ] Location table: coordinates/name, parsed string, result
    * [ ] README entry
* [ ] Filtering
    * [ ] README entry: explain/discuss/justify each step
    * [ ] checkM
        * [ ] diff. env. and req. -> needs python 2.X
        * [ ] add to requirements (https://anaconda.org/bioconda/checkm-genome): checkm-genome=1.0.7
        * [ ] download: https://data.ace.uq.edu.au/public/CheckM_databases/checkm_data_2015_01_16.tar.gz
        * [ ] checkm data setRoot: data/checkm/data
        * [ ] marker: checkm taxon_set domain Bacteria data/checkm_marker.txt
        * [ ] create a FASTA file and split it into individual FASTAs
        * [ ] checkm analyze -x fna -t 30 data/checkm_marker.txt data/checkm/fasta/2018_09_03 data/checkm/output/2018_09_03
        * [ ] checkm qa -t 20 data/checkm_marker.txt data/checkm/output/2018_09_03
            - https://github.com/Ecogenomics/CheckM/wiki/Reported-Statistics
* [ ] DB updates for annotations etc.
    * [ ] abricate
    * [ ] pMLST
    * [ ] checkM
* [ ] End phase
    * [ ] Env. testing
    * [ ] Pipeline testing