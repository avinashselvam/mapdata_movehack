# mapdata_movehack
analysis of high resolution map data provided by the contest

Since no labelling was provided I went ahead with a KMeans clustering hoping it will classify land, trees etc. Being grayscale image this approach didnt help much

![Plain KMeans](https://github.com/avinashselvam/mapdata_movehack/blob/master/first.png)

Later I used pix2pix network which had pretrained weights to work on map data (BtoA). This yeilded good results and applying KMeans on this proved to be really useful and did what I had hoped to do previously

![pix2pix](https://github.com/avinashselvam/mapdata_movehack/blob/master/movehack.png)

