## 2022-08-03  
对reg_loss进行改动，取消reg_loss的注释，希望可以得到论文中的结果  
在不使用reg_loss的情况下  
| 指标miou | cam score | aff cam score | segs score |
| ---  | ---    | --- | ---|
| w/o reg loss |  62.56 | 64.12 | 62.93 |
| w reg loss |  63.75 | 64.85 | 63.08 |

