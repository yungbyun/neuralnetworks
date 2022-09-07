# Sample codes

* https://github.com/yungbyun/myml
* Code replacement
```
import tensorflow as tf
```
> Replace the above code with the below.
```
import tensorflow.compat.v1 as tf
tf.disable_v2_behavior()
```

