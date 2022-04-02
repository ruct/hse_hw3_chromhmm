# hse_hw3_chromhmm

## Колаб

[Ссылка на Google colab](https://colab.research.google.com/drive/1yp4cT308rtCURh4vi1DeMkBXjN8IqC0M?usp=sharing)

## Files and names

|     Клеточная линия    | Гистоновая метка | Название файла | Короткое название |
| ----------- | ----------------- | ----------------- | ----------------- |
| A549 | Control	| wgEncodeBroadHistoneA549ControlDex100nmAlnRep1.bam	| A549Control.bam
| A549 | H2AZ       | wgEncodeBroadHistoneA549H2azDex100nmAlnRep1.bam | H2AZ.bam
| A549 | H3K04me1	| wgEncodeBroadHistoneA549H3k04me1Dex100nmAlnRep1.bam	| H3k04me1.bam
| A549 | H3K04me2	| wgEncodeBroadHistoneA549H3k04me2Dex100nmAlnRep1.bam	| H3k04me2.bam
| A549 | H3K04me3	| wgEncodeBroadHistoneA549H3k04me3Dex100nmAlnRep1.bam	| H3k04me3.bam
| A549 | H4K20me1	| wgEncodeBroadHistoneA549H4k20me1Etoh02AlnRep1.bam	| H4k20me1.bam
| A549 | H3K27ac	| wgEncodeBroadHistoneA549H3k27acDex100nmAlnRep1.bam	| H3k27ac.bam
| A549 | H3K27me3	| wgEncodeBroadHistoneA549H3k27me3Dex100nmAlnRep1.bam	| H3k27me3.bam
| A549 | H3K36me3	| wgEncodeBroadHistoneA549H3k36me3Dex100nmAlnRep1.bam	| H3k36me3.bam
| A549 | H3K79me2	| wgEncodeBroadHistoneA549H3k79me2Dex100nmAlnRep1.bam	| H3k79me2.bam
| A549 | H3K09me3	| wgEncodeBroadHistoneA549H3k09me3Etoh02AlnRep1.bam	| H3k09me3.bam

## ChromHMM

|       Overlap      | Emissions | Transitions |
| ----------- | ----------------- | ----------------- |
| ![img1](https://github.com/ruct/hse_hw3_chromhmm/blob/master/data/A549_10_overlap.png) | ![img2](https://github.com/ruct/hse_hw3_chromhmm/blob/master/data/emissions_10.png) | ![img3](https://github.com/ruct/hse_hw3_chromhmm/blob/master/data/transitions_10.png) |

|       RefSeqTES_neighborhood      | RefSeqTSS_neighborhood |
| ----------- | ----------------- |
| ![img4](https://github.com/ruct/hse_hw3_chromhmm/blob/master/data/A549_10_RefSeqTES_neighborhood.png) | ![img5](https://github.com/ruct/hse_hw3_chromhmm/blob/master/data/A549_10_RefSeqTSS_neighborhood.png) |

## Epigenetic states

![img6](https://github.com/ruct/hse_hw3_chromhmm/blob/master/data/states.png)
![img7](https://github.com/ruct/hse_hw3_chromhmm/blob/master/data/browsed.png)

По позициям состояний сделали выводы об их значениях:
| State | Название | Значение |
| ---- | ---- | ---- |
| 1 | Promoter | Промоутер активный |
| 2 | Weak promoter | Промоутер слабый |
| 3 | Transcribed start | Начало транскрибирующегося генома |
| 4 | Intron | Интрон в активном гене |
| 5 | Transcribed | Активный ген |
| 6 | Transcribed | Активный ген |
| 7 | Transcribed end | Конец активного генома |
| 8 | Repressed | Репрессированный хроматин |
| 9 | Heterochromatin | Межгенное пространство |
| 10 | Heterochromatin | Репрессированный хроматин, межгенное пространство |

