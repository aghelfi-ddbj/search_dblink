# Search dblink_ddbj
Search engine across dblink_ddbj database (psql version)

### Requirement:
input file name: input_filename.txt <br>
format: txt, with one column. Each query in a new line.<br>
observation: WGS, TSA data use only prefix and version, like BPOT01 and IAAA01.<br>

Example: 
```
MTBKS201
IAAA01
PRJDB4182
PRJDB7724
SAMD00388930
AB025938
E-GEAD-284
IAAA01
BPOT01
DRX001133
```
### Usage (only ddbjs1):
In the same directory where file "input_filename.txt", copy the command line below: <br>
```
sh /home/andreaghelfi/scripts/dblink_ddbj/search_dblink
```
### Output files HTML format:
directory name: out_dblink_ddbj <br>
Copy the files with html extension in your local PC, open using a web browser.<br>

### Output files csv format:
directory name: temp_dblink_ddbj <br>
