src/lib/assets contains both 'bg-img.jpeg' and 'bg img.jpeg'.

In src/routes/+page.svelte there is a variable that holds the image url.
This is passed to the div through inline css. When passing 'bg-img.jpeg' it works, but passing 'bg img.jpeg' doesn't work.
