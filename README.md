# CLUE_R-drop
Implemented R-drop on Chinese CLUE dataset in Tnews text classifacation and AFQMC question matching task.
This is a homework for my university course. You can refer to my report here: https://vsmnahh4zr.feishu.cn/docx/doxcnpOoMloLXlW8qanH8hTMjIe

The implementation results are as follows (training and evaluation logs are included in results):
|     | Tnews acc  | AFQMC acc |
|  ----  | ----  | ---- |
| BERT-base  | 56.58 | 74.05 |
| BERT-base + R-drop alpha=0.1  | **57.00** | **75.16** |
| BERT-base + R-drop alpha=0.3  | 56.71 | 74.67 |
| RoBERTa-base  | 57.52 | 73.60 |
| RoBERTa-base + R-drop alpha=0.1  | **57.67** | **74.49** |

