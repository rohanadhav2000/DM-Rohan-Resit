The smiley faces dataset contains 204 unique images of dimensions 9x9x1 belonging to 3 categories (happy, neutral and sad).
The file "smiley_X.npy" contains the images.
The file "smiley_Y.npy" contains the corresponding classes (0 for sad, 1 for neutral, 2 for happy).
They are serialized with numpy, to load use:
```
X = np.load('path/to/smiley_X.npy')
```

The files "smiley_noisy_X" and "smiley_noisy_Y" contain random noise so should be harder to correctly classify.
