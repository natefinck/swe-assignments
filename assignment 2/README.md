# Chess AI and image GAN

## Chess AI Changes

* Reduced epochs on the training to 10 because it was taking very long to run

* Reduced batch size on the training also because it was taking very long to run

* On the pieces model, I changed the metrics to 'accuracy' because I wanted to see how well the model was performing.

## Chess GAN Changes

* Reshape function in the last code chunk was not working so I changed the (8,8) to (8,104).
