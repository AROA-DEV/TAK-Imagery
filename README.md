![Banner](https://i0.wp.com/www.civtak.org/wp-content/uploads/2018/03/cropped-TAK-CIV-Splash-4.png?w=1470&ssl=1)
# TAK-imagery instructions

you have to get the atak software from the tak.gov page ( you can only access the download page with an account )
these are only satellite images for TAK software ( Wintak and ATAK )

DTED0 World folder has to be zipped and later imported use z-zip or any other software to do it

Then you can import each folder from the repository do not import the full zip since it contains the GitHub properties files
 
# How do I add these maps to ATAK ?

![Goto Import Manager](https://github.com/joshuafuller/ATAK-Maps/blob/master/images/screenshot_2.png?raw=true)


![Locate the ATAK-Maps.zip file](https://github.com/joshuafuller/ATAK-Maps/blob/master/images/screenshot_3.png?raw=true)

!!!! REMEMBER TO NOT UPLOAD THE FULL ZIP FILE BUT EACH FOLDER THAT CONTAINS MAPS SEPARATELY !!!

# Get the maps from a server
These is an example of a functional tack server deployment, were the nodes will autamticaly get the information needed from the closet/or factest relay point (users may also be used as a relay)
```mermaid
graph TD;
    Server-->Relay-1;
    Server-->Relay-2;
    Relay-2-->Relay-3;
    Relay-2-->Relay-4;
    Server-->User-1;
    User-1-->User-2;
    User-1-->User-3;
    Relay-3-->user-4;
    Relay-3-->user-5;
    Relay-4-->user-5;
    User-2-->Relay-4;
```

# ATAK ( Android Team Awareness Kit )

Android Team Awareness Kit, designed to be used in mobile devices with the android system from android 4

![ Screenshots from Android Team Awareness Kit ](https://tak.gov/packs/media/img/uploads/device-demonstration-01-aa3ed3ce2bdcd4507bed3f9c768795d0.png)

Available on most android devices ( do not download it from the Google app store go to the tak.gov page )
![ screenshot ATAK ](https://th.bing.com/th/id/OIP.J7YoZnGyuTBFxJwjFJm7YQHaF5?pid=ImgDet&rs=1)

some devices may need external GPS I recommend the GotennaMESH and meshtastic antennas for communications

# WINTAK ( Windows Team Awareness Kit )

The native version of tak for windows

![ WIndows Team Awareness Kit ](https://www.alsa.mil/Portals/9/Images/article_figures/210701_Figure1.jpg?ver=4qUbQkLEa5TZO2c6KBVhTg%3d%3d)

# Tracking funktion

Track each member from your team, these only work if you have a takserver and each member is connected to it

![ ATAK traking ](https://th.bing.com/th/id/R.a209a94829d5a2ece1e8cae80b732c3d?rik=Ub6ubEhZGe2LHg&riu=http%3a%2f%2finsights.globalspec.com%2fimages%2fassets%2f153%2f7153%2fATAK.jpg&ehk=Rphfhve4Kbv0TRqmK3bWkYtWvKt%2bN%2bpIba8D4FifkLI%3d&risl=&pid=ImgRaw&r=0)

# Live information

Have live reports on weather and satellite images( only available from access to private servers )

![ Live weather reports ](https://th.bing.com/th/id/R.4d00cbb0415eb23d0ea45398752f047e?rik=viJ5e%2fN90S4hOA&pid=ImgRaw&r=0)

# 3d maps

Elevation data with maps

![ elevation data ](https://image.winudf.com/v2/image1/Y29tLmF0YWttYXAuYXBwLmNpdl9zY3JlZW5fNV8xNTk5MDM2NDEyXzA4Mw/screen-5.jpg?fakeurl=1&type=.jpg)
