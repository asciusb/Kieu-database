# Kieu-database

## Source:

http://www.nomfoundation.org


## Contents:

- images_s1.0/kieu-****/*.png

Download link (1 GB):
Character images extracted from the JPG website images, with original scale 1.0.

- graphs_s4.0_d3/kieu-****/*.gxl 

Download link (250 MB):
Graphs extracted from the character images, upscaled with factor 4.0, using a node distance of 3 pixels.

- split/kws/kws_freq_kieu-****.txt

Keywords and their frequency in the train, valid, and test set. They appear at least 3 times in the train set, once in the valid set, and once in the test set.

- split/kws/kws_kieu-****.txt

For each keyword, the three first graphs in the training set. They can be used for template-based keyword spotting.

- split/train/chars_kieu-***_train.txt

Graphs of the training set. The ID "0x20027_kieu-1866_001_71_175_100_200" contains the unicode of the character (0x20027), the book (kieu-1866), the page (001), and the original coordinates x1, y1, x2, y2 (71, 175, 100, 200) before upscaling.

Character frequencies are also indicated in a separate file. Same for the valid and test sets.
