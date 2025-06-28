# Tensor Basics
## Tensor Initialization
### tf.constant
Creates a constant tensor from a tensor like object
For example -
``` python
 tensor_3D = tf.constant([[[1,2,0], [3,4,5]], [[5,8,0],[2,7,0]], [[10, 2, 0], [1, 0, 2]], [[1,3,0], [3,5,-1]]] , dtype=tf.float32)
   ```
This creates a 3D tensor. Output of this line is
```
tf.Tensor(
[[[ 1.  2.  0.]
  [ 3.  4.  5.]]

 [[ 5.  8.  0.]
  [ 2.  7.  0.]]

 [[10.  2.  0.]
  [ 1.  0.  2.]]

 [[ 1.  3.  0.]
  [ 3.  5. -1.]]], shape=(4, 2, 3), dtype=float32)
```
