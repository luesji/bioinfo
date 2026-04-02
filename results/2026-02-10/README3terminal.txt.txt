    1  sudo apt update
    2  sudo apt install git build-essential autoconf automake libtool python3 r-base
    3  apt install emboss exonerate wget muscle
    4  sudo apt update
    5  sudo apt install emboss exonerate wget muscle
    6  ls
    7  sudo apt install emboss exonerate wget muscle
    8  pwd
    9  cd
   10  cd Documentos
   11  cd BIOINFORMÁTICA
   12  ls
   13  ls /home/luesji
   14  ls/home/luesji
   15  cd/home/luesji
   16  cd/luesji
   17  ls /home
   18  ls /luesji
   19  cd: luesji
   20  cd luesji
   21  mkdir Bioinformática
   22  ls /home
   23  pwd
   24  ls -1
   25  cd Documentos/
   26  cd Bioinformática
   27  rm Bioinformática
   28  cd..
   29  cd ..
   30  ls 
   31  pwd
   32  cd Bioinformática
   33  mkdir bioinfo
   34  cd bioinfo
   35  mkdir data
   36  ls
   37  mkdir doc
   38  mkdir results
   39  cd results
   40  mkdir 2026-01-29
   41  mkdir 2026-02-03
   42  cd 2026-01-29
   43  firefox
   44  sudo apt install firefox
   45  git--version
   46  apt install git
   47  sudo apt install git
   48  git --version
   49  git config --global user.name luesji
   50  git config --list
   51  git config --global user.email luesji@alumni.uv.es
   52  git config --list
   53  git config --global core.editor "nano -w"
   54  git config --list
   55  git config --global init.defaultBranch soca
   56  git config --list
   57  pwd
   58  cd Bioinformática
   59  cd bioinfo
   60  git init
   61  git status
   62  git add results
   63  git status
   64  git commit -m "Iniciada la segunda práctica, aunque el alineamiento no está hecho todavía"
   65  git status
   66  git log
   67  nano .gitignore
   68  git status
   69  git log
   70  git add .
   71  git staus
   72  git status
   73  nano README.md
   74  nano LICENSE.txt
   75  ssh-keygen -t ed25519 -C luesji@alumni.uv.es
   76  cat /home/luesji/.ssh/id_ed25519
   77  cat /home/luesji/.ssh/id_ed25519.pub 
   78  history > archivo.txt
   79  pwd
   80  ls -1
   81  cd home
   82  cd bin
   83  cd
   84  pwd
   85  ~/bin$ls -1
   86  ~/bin$ ls -1
   87  ~/bin $ls -1
   88  ~/bin $ls-1
   89  wget http://opengene.org/fastp/fastp
   90  chmod a+x ./fastp
   91  ./fastp
   92  pwd
   93  cd Bioinformática
   94  cd bioinfo
   95  cd bin
   96  cd
   97  cd Bioinformática
   98  cd bioinfo
   99  cd bin
  100  git clone https://github.com/lh3/bwa.git
  101  cd bwa
  102  make
  103  cd bin
  104  cd
  105  cd Bioinformática
  106  cd bioinfo
  107  cd bin
  108  sudo apt install samtools
  109  git clone https://github.com/freebayes/freebayes.git
  110  cd freebayes
  111  cd bioinfo
  112  cd
  113  cd Bioinformática
  114  cd bioinfo
  115  cd results
  116  cd 2026-02-10
  117  if [ ! -e DRR025089_1.fastq.gz ]; then
   wget -o /dev/null         ftp://ftp.sra.ebi.ac.uk/vol1/fastq/DRR025/DRR025089/DRR025089_1.fastq.gz; fi
  118  cd
  119  if [ ! -e DRR025089_1.fastq.gz ]; then    wget -o /dev/null         ftp://ftp.sra.ebi.ac.uk/vol1/fastq/DRR025/DRR025089/DRR025089_1.fastq.gz; fi
  120  cd Bioinformática
  121  cd bioinfo
  122  cd results
  123  cd 2026-02-10
  124  ls -1
  125  if [ ! -e DRR025089_2.fastq.gz ]; then    wget -o /dev/null         ftp://ftp.sra.ebi.ac.uk/vol1/fastq/DRR025/DRR025089/DRR025089_2.fastq.gz; fi
  126  ls -1
  127  zless
  128  gunzip -c DRR025089_1.fastq.gz
  129  ls -1
  130  gunzip -c DRR025089_2.fastq.gz
  131  cw
  132  ls -1
  133  cw DRR025089_1.fastq.gz
  134  cd
  135  cd Bioinformática
  136  cd bioinfo
  137  cd data
  138  if [ ! -e referencia.fa ]; then    wget -o /dev/null -O referencia.fa         https://www.ebi.ac.uk/ena/browser/api/fasta/GCA_042137995.2 ; fi
  139  ls -1
  140  cwrl
  141  wc -1 DRR025089_1.fastq.gz
  142  cd
  143  cd Bioinformática
  144  cd bioinfo
  145  cd data
  146  ls -1 | wc -1
  147  wc -l DRR025089_1.fastq.gz
  148  wc -l DRR025089_2.fastq.gz
  149  if [ ! -e fastp.html ]; then    fastp -i DRR025089_1.fastq.gz          -o DRR025089_1_clean.fastq          -I DRR025089_2.fastq.gz          -O DRR025089_2_clean.fastq          --merge          --merged_out DRR025089_m_clean.fastq; fi
  150  if [ ! -e fastp.html ]; then   ./fastp -i DRR025089_1.fastq.gz          -o DRR025089_1_clean.fastq          -I DRR025089_2.fastq.gz          -O DRR025089_2_clean.fastq          --merge          --merged_out DRR025089_m_clean.fastq; fi
  151  CD
  152  cd
  153  if [ ! -e fastp.html ]; then   ./fastp -i DRR025089_1.fastq.gz          -o DRR025089_1_clean.fastq          -I DRR025089_2.fastq.gz          -O DRR025089_2_clean.fastq          --merge          --merged_out DRR025089_m_clean.fastq; fi
  154  cd Bioinformática
  155  cd bioinfo
  156  cd data
  157  if [ ! -e fastp.html ]; then   ./fastp -i DRR025089_1.fastq.gz          -o DRR025089_1_clean.fastq          -I DRR025089_2.fastq.gz          -O DRR025089_2_clean.fastq          --merge          --merged_out DRR025089_m_clean.fastq; fi
  158  if [ ! -e fastp.html ]; then   fastp -i DRR025089_1.fastq.gz          -o DRR025089_1_clean.fastq          -I DRR025089_2.fastq.gz          -O DRR025089_2_clean.fastq          --merge          --merged_out DRR025089_m_clean.fastq; fi
  159  cd
  160  git status
  161  pwd
  162  cd Bioinformática
  163  cd bioinfo
  164  git status
  165  cd
  166  history> archivo.txt
