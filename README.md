# segmentation

* project for image segmentation research with PyTorch
## UNet_cell.ipynb
* UNet 모델 사용
* ISBI_2012 전자 현미경 세포데이터 segmentation 분석
* Training complete in 3m 0s
* Best val loss: 0.591171

## dice_efficient.ipynb
* ISBI 전자 현미경 세포데이터 segmentation 분석
* UNet_cell.ipynb 코드에서 손실함수를 dice_loss로 변경 - 평가지표 : dice_efficient
* Training complete in 2m 56s
* Best val loss: 0.196628
