---
title: Front End Javascript- Working with APIs and IP Addresses
order: 2
---
## GeoIP API
To start, I wanted to briefly introduce the [API](https://freegeoip.app/json/) we will be working with to determine the latitude and longitude in the IP Address. Feel free to click on the link to explore what the else API can be used for.  


![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/4yrdfinc56ocmtz09nga.png) 

As you can see, we set the URL of the API as our location endpoint in our constructor of our LocationFromIP.js class, then: 

## IPFast API

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/n50chbhwg52rdjlf2mxu.png)

Note, in the UpdateUserIP method of the UserIP.js class, the functionality of fetch; it grabs (or, fetches) the other [API](https://ip-fast.com/api/ip/?format=json&location=True) we are using to lookup the IP (`this.ipLookUp`) and returns the information (the IP address) if it can.

## Working with both APIs

![Image description](https://dev-to-uploads.s3.amazonaws.com/uploads/articles/sc5z6xoosopqsf7ab1u1.png)

We work inside of the getGEOIPData method to fetch which data points we want to retrieve from the GeoIP API, such as long (longitude), lat (latitude), city, and region. To make it easier later, I also declared them as variables. Note the usage of the IPFast API here as well, as seen in the lines: 
`const IPClass = new UserIP();
 const userIPData = await IPClass.updateUserIP();`. 

Ideally, after the location is pulled from the GeoIP API, and the IP is pulled from the IPFast API, it should be able to be output later in the `render()` method when you want to show a map. 

## ...Did it work?
If you're lucky, yes! But did mine? Not quite. 
I will admit, I found this exercise to be very tricky and am not entirely sure I understand everything completely. If you want to try to check it out for yourself, feel free to check out this project on my [GitHub](https://github.com/hek5118/ip-project)!