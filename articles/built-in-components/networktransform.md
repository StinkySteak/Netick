# Network Transform

Network Transform is a built-in component to network the `Transform` component. It syncs the position and rotation of the `Transform`.

## Settings:

- Render Transform: assign here the transform that you want to use to display smoothed movement. Should be a child of this GameObject.
- Settings: the replications settings of the NetworkTransform. Choose what you want to sync, and whether you want to enable compression for it or not.
- Interpolation Source: read [here](../interpolation.md#interpolation-source) for a detailed explanation.
- Transform Space: the space used when replicating the data.
- Teleport Distance: the distance at which auto interpolation occurs.
- Precision: the precision of the data compression. 