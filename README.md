# Recursive_Pilon
**Pilonを使用したpolishingを再帰的に15回行うスクリプト**
公式サイト: http://software.broadinstitute.org/software/pilon/
参考URL: http://kazumaxneo.hatenablog.com/entry/2017/10/01/222036 
## installation
```
#pilon==1.23をダウンロード（2019 3/3時点最新）
$ wget https://github.com/broadinstitute/pilon/releases/download/v1.23/pilon-1.23.jar

$ chmod u+x pilon-1.23.jar #実行権を付与

$ pip install -r requirements.txt #condaでのinstallも可
```
## Usage
```
$ . Recur_Pilon.sh FASTA_file FASTQ_file1 FASTQ_file2
```
## Update予定
- thread数と再帰回数を指定可能にする(option化)
- 再帰回数を自動指定にする(polish箇所がなくなるまで再帰的に処理させる)
