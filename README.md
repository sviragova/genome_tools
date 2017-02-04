# genome_tools
my genomics scripts

example usage: 

```
echo "name,count" > my_file.csv
for fasta in data/*.fa ; do
  count=$( bash count_seq.sh $fasta )
  echo "$fasta,$count"
done >> my_file.csv
```
 
