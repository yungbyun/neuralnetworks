# How to run the sample codes in Kaggle.com

* Sample codes: https://github.com/yungbyun/myml

* Code replacement

```
> import tensorflow as tf
```

> Replace the below code with this.

```
> # 기존 코드의 맨 위에 있는 import tensorflow as tf 코드를 아래 두 줄 코드로 바꾸세요.
> import tensorflow.compat.v1 as tf
> tf.disable_v2_behavior()
```

