# Search dblink_ddbj
Search engine across dblink_ddbj database (psql version)

### Requirement:
input file name: input_file.txt <br>
format: txt, with one column. Each query in a new line.<br>
observation: WGS, TSA data use only prefix and version, like BPOT01 and IAAA01.<br>

Example: 
```
cat input_file.txt 
```
```
SAMD00003106
SAMD00388901
PRJDB11873
PRJDB7724
PRJDB9849
BPOT01
PRJDB4182
SAMD00334872
MTBKS201
E-GEAD-284
IAAA01
DRR047016
FY261933
```
### Usage (only ddbjs1):
In the same directory where file "input_file.txt", copy the command line below: <br>
```
bash /home/andreaghelfi/scripts/dblink_ddbj/search_dblink
```
### Output files HTML format:
directory name: out_dblink_ddbj <br>
trace_dblink.html  <br>
trad_dblink.html <br>
gea_dblink.html  <br>
mtb_dblink.html  <br>
Copy the files with html extension in your local PC, open using a web browser.<br>

Example of trad_dblink output file: <br>
[html format](https://github.com/aghelfi-ddbj/search_dblink/blob/main/trad_dblink.html) <br>
[print screen format](https://github.com/aghelfi-ddbj/search_dblink/blob/main/trad_dblink_sample.png) <br>

### Output files csv format:
directory name: temp_dblink_ddbj <br>
all_trace.csv <br>
all_trad.csv <br>
gea2dblink.csv <br>
mtb2dblink.csv <br>
