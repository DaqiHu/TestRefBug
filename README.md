# Test CopyAssetRef bug



Step 1: an empty project

![1728401878339](image/README/1728401878339.png)

Step 2: Create `BP_TestActor` and `BPI_TestInterface`.

![1728402005667](image/README/1728402005667.png)

![1728402041692](image/README/1728402041692.png)

Step 3: Works as normal

![1728402070539](image/README/1728402070539.png)

Step 4: Perform Get Asset Dependencies

![1728402109018](image/README/1728402109018.png)

![1728402133917](image/README/1728402133917.png)

Step 5: Copy uasset files to `/Content`

![1728402162154](image/README/1728402162154.png)

![1728402204135](image/README/1728402204135.png)

Step 6: Get Compile Error

![1728402234573](image/README/1728402234573.png)
