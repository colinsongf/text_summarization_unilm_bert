use limit word

python train_limit_vocab.py --folder_path='E:\data\test_for_UNILM' --task_name='UNILM_1111'
  --config_name='bert-base-chinese-config.json'
  --vocab_name='bert-base-chinese-vocab.txt'
  --model_name='bert-base-chinese-pytorch_model.bin'
  --limit_vocab
  --limit_vocabulary_name='bert-0-chines-pytorch_model.bin'
  --limit_vocab_model_name='bert-0-chines-pytorch_model.bin'
  --use_cuda