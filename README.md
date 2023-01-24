## Algal Bloom Detection

#### NDCI [Normalized Difference Chlorophyll Index] Index is used to detect the Algal bloom.
#### The Steps carried out to achieve that are as follows:
#### 1. Apply Cloud mask function to Image collection
#### 2. Apply NDCI function
#### 3. Mask Image collection with values greater than or equal to 0 since we are intreseted in chlorophyll content.
#### 4. Get the Pixel count on every Satellite passing day
