# vatt_mosi
modification of original [vatt repository](https://github.com/google-research/google-research/tree/master/vatt) for mosi dataset


cmd: 

    python -m vatt.main --task=finetune --mode=train --model_dir=dir\to\pretrained_model --model_arch=Vit_Large --strategy_type=mirrored
