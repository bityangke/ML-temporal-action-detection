# ML-temporal-action-detection

Using the proposal scores I evaluate the detection performance by running
python eval_detection_results.py activitynet1.2 result.bin
This script will report the detection performance in terms of mean average precision at different IoU thresholds.

Requirements:
python >= 3.6
pytorch 0.2
