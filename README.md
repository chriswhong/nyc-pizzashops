# nyc-pizzashops
Sample dataset for the [dangit](https://github.com/chriswhong/dangit) project.  

Individual records are stored as geojson features with filename `{uid}.json`

Please fork this repo, add or edit pizza shops using one of the existing records as a template, and build the distribution file using [dangit](https://github.com/chriswhong/dangit).  Then submit a pull request.

The current schema includes:
`name` - The name of the pizza shop
`uid` - The unique id for the record
`biggestfan` - The biggest fan of this pizza shop - feel free to unseat others and make yourself the biggest fan
`rating` - The rating (1-10) of the pizza shop - this is completely subjective and based on your opinion, or nothing at all
 
Geometry should be a geojson point.
