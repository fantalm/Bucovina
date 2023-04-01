# Bucovina


## Purpose

The purpose of this application is to help promote the travel services of 4 funky tour guides in the Bucovina region(Romania), each of them having distinct key roles. Also as a secondary objective the website could serve as an info point for tourist that travel to Bucovina and would like to know more about the places of interest in the region.


![Screenshot of Bucovina site run through https://ui.dev/amiresponsive?url=https://fantalm.github.io/Bucovina/index.html](./assets/images/readme_photos/amiresponsive.png)


## Features

### Existing features

#### Home page

On the landing page we have the hero image, a photo of a valley in Bucovina covered in fog. I chose this photo because it is emblematic for the beatifull landscapes of Bucovina and so it supports the purpose of the website. For this reason and for consistency I chose to display this image on all 5 pages of the website.
Right below the hero image we have the navigation bar.

**1. Navigation Bar**

The navigation bar consists of 5 buttons displayed horizontally on resolutions greater than 900px and vertically for lower resolutions. 

1. Home
2. Places of interest
3. Tours schedule
4. Bookings
5. Contact us

![Screenshot of hero image and navigation bar and About us section](./assets/images/readme_photos/index_feature_1.png)

**2. About us**

The "About Us" section consists of a photo of the 4 tour guides and a short description of their roles.

**3. About Bucovina**

In this section I gave a brief description of Bucovina providing 3 more photos that encapsulate the beauty of nature and simple life-style and a historical map of the province. 
Apart from the stunning landscape photos the key aspect of this section is the video about Bucovina taken from the youtube channel called [FramingReality](https://www.youtube.com/@FramingReality).

![Screenshot of About Bucovina section](./assets/images/readme_photos/index_feature_2.png)

**4. Footer**

The footer contains social media buttons and my email address. The footer is present on each page for a plus of consistency.

![Screenshot of footer section](./assets/images/readme_photos/index_feature_3.png)


#### Places of interest page

On the second page called Places of interest we have the following features:

1. Accomodations
2. Monasteries and museums
3. Natural landmarks

**1. Accomodations**

In this sections there are a few recommandations for hotels and B&B's with links to their page on the [Bookings.com](wwww.bookings.com.)
I have used [Bitly](https://bitly.com/) to shorten the external links to [Bookings.com](wwww.bookings.com.)

![Screenshot of Accomodation](./assets/images/readme_photos/accomodations.png)

**2. Monasteries and museums**

In this section there are photos and links to [Wikipedia](www.wikipedia.org)(for Voronet and Putna Monasteries) or to [Muzee de la sat](https://muzeedelasat.ro/) for Cacia Salt Mine and to [Explore Bucovina](https://explorebucovina.com/the-bukovina-village-museum/) for the Village Museum. All the links are opening in a new tab and have the "aria-label" attribute set.


![Monasteries and museums](./assets/images/readme_photos/Monasteries_and_museums.png) 

**3. Natural landmarks**

In this section, styled like the above Monasteries section we can find other atractions that the web application is set to promote. The external links used in this section are as follows:
*[Wikipedia](www.wikipedia.org) for : - "The stones of the Lady" landmark
                                      - Suceava castle
                                      - Bicaz canyon
*[Mocanita](https://mocanitamoldovita.com/) for the *Mocanita* lumber train
*[The Campulung Moldovenesc city website](https://campulungmoldovenesc.ro/descopera/cheile-moara-dracului) for the Devil's Mill passage

The photos on this page are nested in the anchor tag so that when clicked the browser opens the above mentioned links in new tabs.

![Natural landmarks feature](./assets/images/readme_photos/natural_landmarks.png)

#### Tour schedule page

This page has 2 sections, one is for the Historical tour and the other one is for the Trails and salt mine tour. The *Historical tour* is set to promote the Monasteries and Museums presented in the Places of interest page, whereas the *Trails and salt mine tour* is a nature oriented experience and promotes the landmarks from the previous webpage.

Both sections consists of a schedule table, the price for each tour, a *price breakdown* section and a button that sends the user to the Bookings page.

To improve responsiveness, I chose not to display the *Duration* column on displays with a resolution lower than 550px.

![historical Tour](./assets/images/readme_photos/historical_tour.png)
![Trails Tour](./assets/images/readme_photos/trails_tour.png)


















