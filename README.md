# LAM-DPA-And-DP-Train-Script
The large-scale model used in DPA2 was obtained from the AISquare model repository, available at:
[https://www.aissquare.com/models/detail?pageType=models&name=DPA-2.3.1-v3.0.0rc0&id=287
﻿](https://www.aissquare.com/models/detail?pageType=models&name=DPA-2.3.1-v3.0.0rc0&id=287)
The model was fine-tuned using a pre-trained medium-scale checkpoint. The training was performed with the following command:
dp --pt train input_finetune.json --finetune DPA2_medium_28_10M_rc0_AIS.pt --model-branch Domains_Alloy
