# spotify test

6 CASES TEST CHECK :


1. Send an insert with a product type of 'album' 
 TC : ID

2. Send an update to add a new territory to the same UPC and change the product type to 'ep' 

<ReleaseType> Namespace = "PDID spotify"
userdefinedvalue="ep"
userdefined
</ReleaseType>

TC : ID and MY

3. Send an update to set a global timed release for all tracks on the same UPC and change the product type to 'single' 

TC : Worldwide

4. Send an update to remove streaming rights to track 1 on the same UPC and change the product type to 'compilation' 

<ReleaseType> Namespace = "PDID spotify"
userdefinedvalue="compilation"
userdefined
</ReleaseType>

5. Send a takedown for the whole product 
RoghtsPercen : 0.00


6. Send an Insert with a genre of 'classical' under a different UPC 
TC : ID
