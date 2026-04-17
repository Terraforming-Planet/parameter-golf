# Non-Record Submission: V5 SP1024 + Seq4096 (1xH100)

This is a non-record submission for OpenAI Parameter Golf.

It documents a V5 run on the official FineWeb sp1024 path using a longer sequence length (`TRAIN_SEQ_LEN=4096`) and a single H100 GPU. This submission does **not** claim record-track status, because it was not produced under the official 10-minute / 8xH100 record-setting condition.

## Summary

- Run ID: `v5_sp1024_top10_a`
- Track: `non-record-16mb`
- GPU: `1xH100`
- Final exact `val_bpb`: **1.21430168**
- Final exact `val_loss`: **2.05029752**
- Total submission size: **15841388 bytes**

## Included files

- `README.md`
- `submission.json`
- `results.tsv`
- `train_gpt.py`
- `train.log`
- `final_model.int8.ptz`
