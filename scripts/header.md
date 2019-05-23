## slurm header

<pre style="color: silver; background: black;">
#!/bin/bash
#SBATCH --job-name=stringTie_FPKM
#SBATCH -n 1
#SBATCH -N 1
#SBATCH -c 4
#SBATCH --mem=30G
#SBATCH --partition=general
#SBATCH --qos=general
#SBATCH --mail-type=ALL
#SBATCH --mail-user=
#SBATCH -o %x_%A.out
#SBATCH -e %x_%A.err
</pre>
