---
title: "Used Car Dataset Description"
author: "Luc Frachon"
date: "February 8, 2017"
output: html_document
---

The dataset used in this project was found on [Kaggle](https://www.kaggle.com/orgesleka/used-cars-database). The author of the dataset scraped over 370,000 used car ads from the German eBay website.

The data contains the following fields (adapted from the description found on Kaggle):

- dateCrawled: When this ad was first crawled, all field values are taken as of this date [2016-03-05 14:06:22 UTC - 2016-04-07 14:36:58:UTC]
- name: Free text, title of the ad
- seller: Private or professional seller
- offerType: Purchase or sell
- price: The price on the ad to sell the car [0 - 2,147,483,647]
- abtest: Unclear - probably an internal flag to eBay to identify participants in an A/B test
- vehicleType: Body style of the vehicle [categorical]
- yearOfRegistration : What year was the car first registered [1000 - 9999]
- gearbox: Transmission style [categorical]
- powerPS: Power output of the car in PS [0 - 20,000]
- model: The car's model name [categorical]
- kilometer: mileage of the car in kilometers [5,000 - 150,000]
- monthOfRegistration : Month when the car was first registered [0 - 12]
- fuelType: Fuel used by the car [categorical]
- brand: Brand of the car (manufacturer's name) [categorical]
- notRepairedDamage: Whether the car has unrepaired damage [categorical]
- dateCreated: Date of ad posting [2014-03-10 - 2016-04-07]
- nrOfPictures: Number of pictures in the ad (unfortunately this field contains only 0s and is thus useless (bug in crawler!))
- postalCode: German postcode of user posting the ad
- lastSeen: When the crawler last saw this ad [2016-03-05 14:15:08 - 2016-04-07 14:58:51]

The dataset contains 20 variables and 371,824 observations in total.