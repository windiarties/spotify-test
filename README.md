# spotify test
6 cases test
24-03-2020


1. Send an insert with a product type of 'album' 
ID

(DONE)

2. Send an update to add a new territory to the same UPC and change the product type to 'ep' 

<ReleaseType> Namespace = "PDID spotify"
userdefinedvalue="ep"
userdefined
</ReleaseType>

territory >> ID and MY 

(DONE)

3. Send an update to set a global timed release for all tracks on the same UPC and change the product type to 'single' 

territory >> worldwide
rightpercen 100

(DONE)

4. Send an update to remove streaming rights to track 1 on the same UPC and change the product type to 'compilation' 

<ReleaseType> Namespace = "PDID spotify"
userdefinedvalue="compilation"
userdefined
</ReleaseType>

rightpercen (track 1 =0) 
others 100.00

(DONE)

5. Send a takedown for the whole product 
worldwide
rightpercen semua 0

(DONE)


6. Send an Insert with a genre of 'classical' under a different UPC 

(DONE)
