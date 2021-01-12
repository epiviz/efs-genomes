 genomes files for epiviz file server

created using the cli script from efs

```
efs build_genome --ucsc=hg19 --output=./hg19
```

replace hg19 with other genome builds.

To add the genomes to efs, use type `efs-dir`

```
genome = mMgr.add_genome("hg38", url=os.getcwd() + "/genomes/hg38", type = "efs-dir")
genome = mMgr.add_genome("hg19", url=os.getcwd() + "/genomes/hg19", type = "efs-dir")
genome = mMgr.add_genome("mm10", url=os.getcwd() + "/genomes/mm10", type = "efs-dir")
genome = mMgr.add_genome("mm9", url=os.getcwd() + "/genomes/mm9", type = "efs-dir")

```
