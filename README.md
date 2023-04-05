# hse_hw3

[Ссылка на колаб](https://colab.research.google.com/drive/1vuickhmV3VM2HlXnig1cbKTKwnJ4Xv10?usp=sharing).

Клеточная линия: A549

Контроль: wgEncodeBroadHistoneA549ControlEtoh02AlnRep2.bam

10 гистоновых меток:
- wgEncodeBroadHistoneA549CtcfEtoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H2azEtoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k04me1Etoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k04me2Etoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k04me3Etoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k09acEtoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k27acEtoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k36me3Etoh02AlnRep2.bam
- wgEncodeBroadHistoneA549H3k79me2Etoh02AlnRep2.bam

## [cellmarkfiletable.txt](data/cellmarkfiletable.txt)

Клеточная линия | Гистоновая метка | Файл с гистоновой меткой | Файл с контролем
--- | --- | --- | ---
A549 | Ctcf | Ctcf.bam | Control.bam
A549 | H2az | H2az.bam | Control.bam
A549 | H3k04me1 | H3k04me1.bam | Control.bam
A549 | H3k04me2 | H3k04me2.bam | Control.bam
A549 | H3k04me3 | H3k04me3.bam | Control.bam
A549 | H3k09ac | H3k09ac.bam | Control.bam
A549 | H3k09me3 | H3k09me3.bam | Control.bam
A549 | H3k27ac | H3k27ac.bam | Control.bam
A549 | H3k36me3 | H3k36me3.bam | Control.bam
A549 | H3k79me2 | H3k79me2.bam | Control.bam

## [Папка с выдачей ChromHMM](/data)

### Emissions

![Image](/data/emissions_15.png) 

### Overlap

![Image](/data/A549_15_overlap.png)

### Transitions

![Image](/data/transitions_15.png)

### RefSeqTSS

![Image](/data/A549_15_RefSeqTSS_neighborhood.png)

### RefSeqTES

![Image](/data/A549_15_RefSeqTES_neighborhood.png)

## Genome Browser

![Image](/data/1.png)

Тип | Название | Куда попадает
--- | --- | ---
1 | Insulator | H3K36m3, H3K36m3
2 | Insulator | H3K36m3, H3K79m2
3 | Insulator |
4 | Weak Transcribed | H3K27ac
5 | Weak Transcribed | H3K36m3
6 | Transcriptional transition |
7 | Polycomb-repressed | H2AZ, H3K27ac
8 | Active Promoter | H3K27ac
9 | Inactive Promoter |
10 | Inactive Promoter |
11 | Weak enhancer |
12 | Weak enhancer | H3K36m3
13 | Weak enhancer | CTCF
14 | Inactive promoter |
15 | Weak Transcribed | CTCF

## Бонус

![Image](/data/2.png)
