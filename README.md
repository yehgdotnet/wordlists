# wordlists
Mirror of known wordlists


for FILE in *.txt; do  john /tmp/hashfile --wordlist=$FILE -format=xxxxxxx; done 
