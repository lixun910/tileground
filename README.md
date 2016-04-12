# tileground
map background



Basemap* basemap = new Basemap(extent, "cartodb");

basemap->pan();
basemap->zoom();

basemap->GetBitmap();
basemap->GetBitmap(extent);

basemap->IsReady();
