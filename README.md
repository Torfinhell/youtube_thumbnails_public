# youtube_thumbnails_public
## This project was aimed to train a model that could predict the title of a youtube video by the thumbnail image
channels.csv - dataset from https://www.kaggle.com/datasets/zhitaochen/channels

thumbnail_collect - notebook creates training_data.csv (ran on colab)

training_data.csv consists of video information like thumbnail url, channel name, channel description, title

thumbnail_train - notebook trains model to predict a title to an animal video using the thumbnail(The notebook was run locally on colab with CUDA Version: 12.6, Driver Version: 560.76 )

## Result:
#### During Training:
![image](https://github.com/user-attachments/assets/61b9b5c3-f9ac-4b38-8f6a-2cb11d0c03d8)

#### Loss for Test_Data: 7.563081352713143
#### Examples(from test_Data):
![image](https://github.com/user-attachments/assets/2543c1fb-8f34-408c-be05-6d67ac5fe75f)

prediction befor training:  ['a black and white cat sitting on top of a tree']

prediction after training:  ['Penguin Adventures From Antarctica to the Galapagos Jungle']

title:  Puffin Burrow  Highlights 2023

![image](https://github.com/user-attachments/assets/b6fff58b-fa39-4e9d-ba74-4dc428650203)

prediction befor training:  ['a dog standing in front of a fence']

prediction after training:  ['Rescue of Starving Dog Who Never Had a Name']

title:  Dog with NO EYES abandoned on the side of the road

![image](https://github.com/user-attachments/assets/2fbc79f4-865e-4f60-be6a-38192e347883)

prediction befor training:  ['a cat sitting next to a bunch of stuffed animals']

prediction after training:  ['Funny Cats and Dogs Hilarious Video #245 😈#shorts#drawing#funny#xiaolumn']

title:  my top video，How do you like it

![image](https://github.com/user-attachments/assets/38040649-84ec-4fed-bb07-b6f3694c291d)

prediction befor training:  ['a cat sitting on top of a birthday cake']

prediction after training:  ['This Cat DESTROYED Fortnite']

title:  🤤Make Delicious Desserts And Juicy Fruits With Me



