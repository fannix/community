# Results

The model was trained on 2 datasets using default configurations provided by original author. For both datasets, trainings are done for fixed 100 epochs, and evaluations are done every 10 epochs. Hardware environment:

- CPU: Intel Xeon E5 2690v4 (1x)
- GPU: NVidia V100 32G PCIe (1x)

Result for METR-LA dataset:

Total time: 3:16 h (actual convergence happens near 50 epochs)

Epoch | Test loss | 15min MAE | 15min MAPE | 15min RMSE | 30min MAE | 30min MAPE | 30min RMSE | 60min MAE | 60min MAPE | 60min RMSE
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
10 | 3.06 | 2.73 | 0.0705 | 5.33 | 3.21 | 0.0892 | 6.62 | 3.85 | 0.1172 | 8.22
20 | 3.065 | 2.73 | 0.0693 | 5.37 | 3.20 | 0.0852 | 6.65 | 3.86 | 0.1072 | 8.22
30 | 2.992 | 2.69 | 0.0687 | 5.28 | 3.11 | 0.0843 | 6.45 | 3.68 | 0.1052 | 7.82
40 | 2.951 | 2.67 | 0.0682 | 5.22 | 3.08 | 0.0833 | 6.37 | 3.59 | 0.1030 | 7.66
50 | 2.939 | 2.68 | 0.0686 | 5.21 | 3.08 | 0.0839 | 6.33 | 3.55 | 0.1030 | 7.53
60 | 2.941 | 2.68 | 0.0687 | 5.21 | 3.08 | 0.0843 | 6.33 | 3.55 | 0.1037 | 7.52
70 | 2.942 | 2.68 | 0.0688 | 5.21 | 3.08 | 0.0843 | 6.33 | 3.55 | 0.1035 | 7.52
80 | 2.943 | 2.68 | 0.0688 | 5.21 | 3.08 | 0.0844 | 6.33 | 3.55 | 0.1034 | 7.52
90 | 2.943 | 2.68 | 0.0688 | 5.21 | 3.08 | 0.0844 | 6.33 | 3.55 | 0.1033 | 7.52
100 | 2.944 | 2.68 | 0.0688 | 5.21 | 3.08 | 0.0844 | 6.33 | 3.55 | 0.1032 | 7.52

Result for PEMS-BAY dataset:

Total time: 7:40 h (actual convergence happens near 40 epochs)

Epoch | Test loss | 15min MAE | 15min MAPE | 15min RMSE | 30min MAE | 30min MAPE | 30min RMSE | 60min MAE | 60min MAPE | 60min RMSE
--- | --- | --- | --- | --- | --- | --- | --- | --- | --- | ---
10 | 1.71 | 1.36 | 0.0282 | 2.93 | 1.80 | 0.0400 | 4.23 | 2.41 | 0.0566 | 5.79
20 | 1.687 | 1.34 | 0.0278 | 2.84 | 1.73 | 0.0385 | 3.96 | 2.18 | 0.0508 | 5.06
30 | 1.651 | 1.33 | 0.0281 | 2.83 | 1.70 | 0.0391 | 3.95 | 2.10 | 0.0516 | 5.01
40 | 1.593 | 1.31 | 0.0275 | 2.76 | 1.66 | 0.0375 | 3.78 | 1.97 | 0.0477 | 4.61
50 | 1.595 | 1.31 | 0.0274 | 2.77 | 1.66 | 0.0375 | 3.79 | 1.97 | 0.0474 | 4.64
60 | 1.595 | 1.31 | 0.0274 | 2.77 | 1.66 | 0.0375 | 3.79 | 1.97 | 0.0474 | 4.63
70 | 1.595 | 1.31 | 0.0274 | 2.77 | 1.66 | 0.0375 | 3.79 | 1.97 | 0.0474 | 4.64
80 | 1.595 | 1.31 | 0.0274 | 2.77 | 1.66 | 0.0375 | 3.79 | 1.97 | 0.0474 | 4.64
90 | 1.595 | 1.31 | 0.0274 | 2.77 | 1.66 | 0.0375 | 3.79 | 1.98 | 0.0474 | 4.64
100 | 1.596 | 1.31 | 0.0274 | 2.77 | 1.66 | 0.0375 | 3.79 | 1.98 | 0.0474 | 4.64