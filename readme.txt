Hi! 
Hopefully this will provide some insight on how I decided to tackle some specific problemas within the challenge.

At first, I started to lay out the foundations by making sure I had a full width header, that was made up of the logo + the company name.

I then realized that this was larger than the actual container for the rest of the page, so I kept it outside of the main container, otherwise it would be only as wide as its parent would be.

I had a few issues with the image, because I didn't want to use specific pixel sizing (it could cause me troubles on different resolutions) and went with the percentage approach.
It wasn't resizing the image properly so I wrapped it in a boostrap div that could hold it and make it sure it wouldnt at least escape my expected proportions.

After that, I started working on the featured content.
I realized five divs wouldnt fit the bootstrap row properly as 12/5 = 2,4... and there was no way of dealing with it properly using boostrap's default. So, I made the first one offset, and then tried to make it behave
as if I had actually 6 columns to deal with.