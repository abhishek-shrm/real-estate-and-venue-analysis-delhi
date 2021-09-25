# real-estate-and-venue-analysis-delhi
It is a clustering analysis project on Real Estate prices and venues of Delhi. In this project, I clustered different areas of Delhi into different groups based on the amenities present in an area and real estate prices. The aim of this project is to help new people settle in Delhi. Whether someone wants to buy a house in Delhi or open a new restaurent, this project will come in handy.

Click [here](https://slides.com/abhishek-shrm/real-estate-and-venues-analysis-delhi/fullscreen) to view the slides on the project.

## Data Sources
- **Real Estate Prices** for different areas in Delhi from the **makaan.com** website.
- **Geocoding API** of **MapMyIndia** to get the latitude and longitude of areas.
- **Foursquare’s Places API** to get venues near a particular location.

## Results of Venues Analysis
<div class="sl-block is-focused" data-block-type="image" style="width: 925px; height: 551px; left: 18px; top: 134px; min-width: 1px; min-height: 1px;" data-origin-id="4ec7566dea0e9021307a1636cc80bf16"><div class="sl-block-content" style="z-index: 11;"><img style="" data-natural-width="1157" data-natural-height="689" data-lazy-loaded="" src="https://s3.amazonaws.com/media-p.slid.es/uploads/1159238/images/6678077/map_cluster.png"></div></div>

- Cluster-0 ![image](https://user-images.githubusercontent.com/33491664/134685213-df001a00-7f45-41a9-948b-2d141297b24b.png) has a higher no. of ATMs, Indian Restaurants, Markets, Shops. These are the locations where people go shopping or hang out.
- Cluster-1 ![image](https://user-images.githubusercontent.com/33491664/134685306-ba05cda1-98f8-4987-8522-2a6d2678dd91.png) has a higher no. of Hotels, Asian Restaurants, Gyms and Neighborhoods. So these are residential areas.
- Cluster-2 ![image](https://user-images.githubusercontent.com/33491664/134685499-6f3c6f05-5839-478d-8ba2-4d9ded41d0fa.png) has a higher no. of Gardens and parks. These areas are greener than other areas.
- Cluster-3 ![image](https://user-images.githubusercontent.com/33491664/134685733-55e25f0e-09f5-46a4-9dd3-3bb3401cfa64.png) has airports and also some high-end facility providers. These areas are downtown and posh areas.
- Cluster-4 ![image](https://user-images.githubusercontent.com/33491664/134685851-9c7f3c23-275a-4d16-8876-49d39a2ee8df.png) has a higher no. of metro stations, pizza places and other businesses. These areas are well-connected areas by metros.

## Results of Real Estate Analysis
<div class="sl-block is-focused" data-block-type="image" style="min-width: 1px; min-height: 1px; width: 937px; height: 564px; left: 12px; top: 66px;" data-origin-id="1eb167aee642ea0d4287e96644108b75"><div class="sl-block-content" style="z-index: 11;"><img style="" data-natural-width="1155" data-natural-height="695" data-lazy-loaded="" src="https://s3.amazonaws.com/media-p.slid.es/uploads/1159238/images/6678076/eco_viz.png"></div></div>

- Rating(0-20)=> Category I ![image](https://user-images.githubusercontent.com/33491664/134686659-609bead9-4095-4b42-a402-7b8e6faf9555.png)
- Rating(21-40)=> Category II ![image](https://user-images.githubusercontent.com/33491664/134686755-1e575307-1b0c-4b2f-a100-5fd51f67735d.png)
- Rating(41-60)=> Category III ![image](https://user-images.githubusercontent.com/33491664/134687059-7b37c80b-41ed-4092-9e99-93de214355e1.png)
- Rating(61-80)=> Category IV ![image](https://user-images.githubusercontent.com/33491664/134687227-2056fa50-3900-4d44-9ece-dadbad8e3116.png)
- Rating(81-100)=> Category V ![image](https://user-images.githubusercontent.com/33491664/134687343-e01ebd86-c7a5-456c-b460-0bed88533642.png)


Higher the prices of houses higher are the chance that people with better economic conditions live in that area.
People living in the area of Category V has the highest economic strength and people living in the area of Category I have lowest economic strength.
