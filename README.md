# TQC + HER for In-Hand Manipulation

```
conda create -n in-hand python=3.10
conda activate in-hand
pip install -r requirements.txt
```

Train `HandManipulateBlockRotateXYZ-v1` with 16 environments
```
python tqc_her_base.py --env-id HandManipulateBlockRotateXYZ-v1 --seed 4 --num-envs 16
```

Train `HandManipulateBlock_ContinuousTouchSensors-v1` with 16 environments
```
python tqc_her_base.py --env-id HandManipulateBlock_ContinuousTouchSensors-v1 --seed 4 --num-envs 16
```
