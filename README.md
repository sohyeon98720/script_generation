# script_generation

### finetuning

```sh
python main.py --epoch=200 --data_file_path=./train.csv --save_path=./checkpoint/ --load_path=./checkpoint/KoGPT2_checkpoint_240000.tar --batch_size=1
```
----------
### generator - cmd

```sh
python generator.py --temperature=1.0 --text_size=100 --load_path=./checkpoint/KoGPT2_checkpoint_240000.tar --tmp_sent="우리는 지난"
```
