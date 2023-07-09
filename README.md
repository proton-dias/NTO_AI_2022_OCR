# NTO_AI_2022_OCR

Prize-winner of the National Technological Olympiad in the AI profile


## Explanation

1) MaskRCNN from baseline, improved. When output, we round the polygons using cv2.approlyDP
2) Retrained model with RCNN hackathon
3) RCNN trained from scratch
4) Beam search with language model
5) Ensemble that we choose from: grid_search 1 model, grid_search 2 model, beam_search 1 model

All CRNN trained until lr is less than 1e-6


### here full inference example:
![input image](https://github.com/proton-bit/NTO_AI_2022_OCR/blob/main/inference_crnn_x.jpg)
![output image](https://github.com/proton-bit/NTO_AI_2022_OCR/blob/main/inference_crnn_y.jpg)
