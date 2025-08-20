# Trans your data to LLaMA data format
### Trans the vce data json format to LLaMA data format:

<!-- python data_trans/vce.py /public/home/sugon_libo/tests/project/ustc-ac/video-llm/data/EmoBench/VCE/vce_dataset/train_labels.json /public/home/sugon_libo/tests/project/ustc-ac/video-llm/data/EmoBench/meta/dataset/train/emo_types_sft/vce.json -->
```
python ./data_trans/vce.py {vce_test_labels.json} {LLaMA_test_labels.json}
```

```
python ./data_trans/vce.py {vce_train_labels.json} {LLaMA_train_labels.json}
```
