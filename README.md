# scala_rle_encoding


Make Rle-encoding function (it is used to compress BMP files)
BMP code every pixel with value. The problem is that sometimes there are many the same values.
Every value is color of pixel. The idea of Rle-encoding is to substitute repeated values.
For example ABCDE will be the same ABCDE, AABBCCDD will be 2A2B2C2D.
