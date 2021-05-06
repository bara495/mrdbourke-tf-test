# mrdbourke-tf-test

Repeated some tests from an ML YouTuber Daniel Bourke to compare some machine's TF running capabilities to M1 Macbook Pro and Air (also MBP 16 Intel)

[Video talking about the test.](https://youtu.be/oqnq8miWVq0) The part with TensorFlow tests beggins at [19:31.](https://youtu.be/oqnq8miWVq0?t=1168)

Mr. Bourke also published an [article on the topic.](https://www.mrdbourke.com/m1-macbook-vs-intel-macbook-speed-comparison/)

| (Bourke's results in s/epoch) | MacBook Air (M1) | MacBook Pro 13-inch (M1) | MacBook Pro 16-inch (Intel) | Google Colab T4 GPU\* | Google Colab (free) |
| ----------------------------- | :--------------: | :----------------------: | :-------------------------: | :-------------------: | :-----------------: |
| Basic CNN                     |       7-8        |           7-8            |            35-41            |           5           |        91-95        |
| Transfer learning             |      20-21       |          20-21           |            59-66            |           7           |                     |
| tensorflow_macos benchmark    |      23-24       |          20-21           |            20-21            |           9           |                     |

\*Google Colab uses pure TensorFlow rather than tensorflow_macos

Feel free to check out Daniel Bourke's [github page](https://github.com/mrdbourke), he has some great ML related repos.
