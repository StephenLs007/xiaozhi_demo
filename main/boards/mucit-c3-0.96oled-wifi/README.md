## 码立创C3主控V2

1、该板卡 flash 大小为 4MB，编译时注意选择合适的分区表：

```
Partition Table  --->
  Partition Table (Custom partition table CSV)  --->
  (partitions_4M.csv) Custom partition CSV file
```
**合并BIN：**

```bash
idf.py merge-bin -o Mucit_AIBOX.bin -f raw 
```