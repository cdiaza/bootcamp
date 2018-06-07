# bootcamp
Code for the Programming Bootcamp

Steps to get things to work

1. Clone repo on Tombo `git clone https://github.com/oist/bootcamp.git` (note the use of the full URL)

2. Create the BLAST database: `makeblastdb -in data/database/Refsoil16s.fa -dbtype nucl -out data/database/My16sAmplicon`

3. Run `python main.py`

4. Run `sbatch data/blastjob.sh`

5. Run `python analysis.py`
