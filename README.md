# FilterByLength

#### Filter fasta sequences by length and count the sequences in a multifasta file



## Usage

```
FilterByLength.py --input input_file.fa --output output_file.fa --length_min 100 --length_max 500 --verbose Y
```


## Output






## Help 


```
usage: FilterByLength.py [-h] -l LENGTH_MIN [-m LENGTH_MAX] -i INPUT [-o OUTPUT] [-v Y/y or N/n] [-V]

Filter multifasta sequences by sequence length

optional arguments: 

-h, --help           	show this help message and exit
-l LENGTH_MIN, --length_min LENGTH_MIN
                     	minimum lenght of sequence to retain
-m LENGTH_MAX, --length_max LENGTH_MAX
                     	max lenght of sequence to retain 
-i INPUT, --input INPUT      
						input fasta file
-o OUTPUT, --output OUTPUT         
						output fasta file  
-v Y/y or N/n, --verbose Y/y or N/n     
						print progress to the terminal (default:verbose)  
-V, --version         show program's version number and exit

```

