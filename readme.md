# Baubles

Baubles is an experimental (and slightly unreliable!) network scanner which you can use to quickly determine some of the devices on your local network which may have web services available.
When a port is unavailable, the browser typically takes a different amount of time to error than it does if a port is available, and again different times if it's filtered. By using 'comparator ports' which we assume are not open but filtered, we can look at the differences between closed, open and filtered and make a best guess based on the timing

On mobiles I've noticed that the difference in times between a filtered and open port is far less distinct, and combined with the odd port closing quicker than "it should", accuracy is often affected. I'll keep tinkering though and see what I can do!

Originally, this was a part of my other project VilNE, however while more recent CORS restrictions have reduced that surface somewhat, I found myself often using the scanning component as a quick and dirty way to find some of the devices on my network to connect to.

Please reach out on twitter etc if you're interested in this work, between this and VilNE I'm still convinced people haven't clocked onto the risk of users being used to proxy attacks against internal resources via the browser.
