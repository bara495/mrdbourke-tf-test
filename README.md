# mrdbourke-tf-test

Repeated some tests from an ML YouTuber Daniel Bourke to compare some machine's TF running capabilities to M1 MacBook Pro and Air (also MBP 16 Intel).

Did the tests with a budget laptop running only on CPU and on free Google Colab CPU.

[Video talking about the test.](https://youtu.be/oqnq8miWVq0) The part with TensorFlow tests begins at [19:31.](https://youtu.be/oqnq8miWVq0?t=1168)

Mr. Bourke also published an [article on the topic.](https://www.mrdbourke.com/m1-macbook-vs-intel-macbook-speed-comparison/)
The Google Colab Notebook can be found [here.](https://colab.research.google.com/drive/1VDLbqnYl2DrwMrIpl4kCwrUbGHnSgpiI?usp=sharing)

| (1st 4 are Bourke's results, all in s/epoch) | MacBook Air (M1) 16GB | MacBook Pro 13-inch (M1) 16GB | MacBook Pro 16-inch (Intel) | Google Colab T4 GPU\* | Google Colab (free) | [2020 Honor MagicBook 14 (R5-3500U, 8GB RAM)](https://www.hihonor.com/global/products/laptop/honor-magicbook14/spec/) |
| -------------------------------------------- | :-------------------: | :---------------------------: | :-------------------------: | :-------------------: | :-----------------: | :-------------------------------------------------------------------------------------------------------------------: |
| Basic CNN                                    |          7-8          |              7-8              |            35-41            |           5           |        91-95        |                                                         59-78                                                         |
| Transfer learning                            |         20-21         |             20-21             |            59-66            |           7           |        78-80        |                                                         53-61                                                         |
| tensorflow_macos benchmark                   |         23-24         |             25-26             |            20-21            |           9           |       130-132       |                                                         80-98                                                         |

\*Google Colab uses pure TensorFlow rather than tensorflow_macos

Feel free to check out Daniel Bourke's [github page](https://github.com/mrdbourke), he has some great ML related repos.
