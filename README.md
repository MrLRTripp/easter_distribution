# easter_distribution

Since Easter Day occurs on the first Sunday after the first full moon after the spring equinox, 
there is a wide range of dates that it can occur on. Luckily, the Census has data on past and future dates that Easter occurs on so we can plot the distribution 
of Easter Days that have occurred between 1600 and 2023.  

I wanted to make it a little more fun, by using the animation methods in Matplotlib. The distrubition chart is built up as the years tick by. 

I used pastel colors that evoke Easter and spring. Matplotlib did not have a continuous pastel color map so I de-saturated the rainbow color map. I also generated a 
Easter basket using the new Bing text-to-image diffusion generator. I used Gimp to remove background and change the aspect ratio from 1:1 to 16:9.

I the used Bing chatbot as an assistant. It could not create exactly what I wanted by itself, but it did provide a good starting point and helped with some 
trickier parts of using Matplotlib. For instance, if I needed a simple example of using plt.figimage() it could quickly generate one much faster than doing it myself
or searching for one.
