# TQC + HER for In-Hand Manipulation

```
conda create -n in-hand python=3.10
conda activate in-hand
pip install -r requirements.txt
```

Train `HandManipulateBlockRotateXYZ-v1` with 16 environments
```
python test_tqc_her.py --env-id HandManipulateBlockRotateXYZ-v1 --num-envs 16
```

