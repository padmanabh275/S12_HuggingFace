# S12_HuggingFace

LOCAL_RANK: 0 - CUDA_VISIBLE_DEVICES: [0] </br>

<br\>  | Name          | Type       | Params </br>
<br\>---------------------------------------------</br>
<br\>0 | prepblock     | Sequential | 1.9 K </br>
<br\>1 | convblock1_l1 | Sequential | 74.0 K</br>
<br\>2 | convblock1_r1 | Sequential | 295 K </br>
<br\>3 | convblock2_l1 | Sequential | 295 K </br>
<br\>4 | convblock3_l1 | Sequential | 1.2 M </br>
<br\>5 | convblock3_r2 | Sequential | 4.7 M </br>
<br\>6 | convblock4_mp | Sequential | 0     </br>
<br\>7 | output_block  | Sequential | 5.1 K </br>
<br\>---------------------------------------------</br>
6.6 M     Trainable params
0         Non-trainable params
6.6 M     Total params
26.292    Total estimated model params size (MB)


  Test metric        ┃       DataLoader 0        ┃
┡━━━━━━━━━━━━━━━━━━━━━━━━━━━╇━━━━━━━━━━━━━━━━━━━━━━━━━━━┩
│         test_acc          │    0.8960000276565552     │
│         test_loss         │    0.4443301260471344     
