# study_pytorch
Based on "つくりながら学ぶ！PyTorchによる発展ディープラーニング"

## Diary
**20220202**
- finish 1-1
- start 1-3
- using Resize, CenterCrop, can cut an image to squere based on its shrter edge
- np.clip makes number in selected range
- google drive mounting is useful to use external data, while using colab, and when pointing at its data, using absolute path. ex)/content/drive/Mydrive/....
- torch→numpy: .detach().numpy()
- transpose((a,b,c)) can use for more than 2 dims
- transforms.RandomResizedCrop can resize to any sizes and generate multiple images
- transforms.RandomHorizontalFlip can reverse the image in half percentage to each image
