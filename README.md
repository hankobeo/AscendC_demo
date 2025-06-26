#### 1、生成算子工程
```
chmod 600 ReduceLogSumExp.json
chmod 700 .
msopgen gen -i ReduceLogSumExp.json -c ai_core-Ascend310P -lan cpp -out ./ReduceLogSumExp
```