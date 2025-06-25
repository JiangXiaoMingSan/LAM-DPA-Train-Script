# LAM-DPA-And-DP-Train-Script

[![Python](https://img.shields.io/badge/python-3.8%2B-3776AB.svg)](https://www.python.org/)

---

## 🔗 Model Source

The pretrained model is hosted on AISquare:

* **DPA-2.3.1-v3.0.0rc0**
  [View on AISquare](https://www.aissquare.com/models/detail?pageType=models&name=DPA-2.3.1-v3.0.0rc0&id=287)

## 🚀 Training Command

Fine-tune the large-scale model with your configuration file:

```bash
dp --pt train input_finetune.json \
   --finetune DPA2_medium_28_10M_rc0_AIS.pt \
   --model-branch Domains_Alloy
```

* `input_finetune.json`: JSON config for your dataset and hyperparameters
* `DPA2_medium_28_10M_rc0_AIS.pt`: AIS model
* `--model-branch`: Specify the model branch (e.g., `Domains_Alloy`)

