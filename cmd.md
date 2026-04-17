### For Qwen2.5-VL (Text + Vision)

```bash
# Step 1: Generate activation scales
python generate_act_scale_shift.py \
    --model weights/Qwen2.5-VL-3B-Instruct \
    --dataset-type text-vision \
    --nsamples 128