# nasa-api-project

In this project, the NASA API is incorporated to get random astronomy pictures of the day. The results will be formatted into cards with an image title, 'Add to Favorites' option, description, date, and copyright information. It will also be possible to view favorites, and load more images which will refresh the page with 10 new images.

To improve performance, images are lazy loaded, loading only when close to being scrolled.

The application will also be mobile responsive.

## What I Learned

* cannot use ```hidden``` element property when using ```display: flex;```; create a ```'hidden' class``` with a ```display: none;``` property, then ```add``` or ```remove``` from ```classlist``` as needed

## Future Modifications and Enhancements

* add a filter to the favorites page
## References and Resources

[Loaf](https://getloaf.io/) (animated SVG icons editor)