# CybersecurityPiscine

This piscine gives small fundamental cybersecurity projects like scraping data from a website and the discovery of metadata, OTP, implementation of a hidden service on tor, reverse engineering, creating a harmless malware, understanding the network from a low-level perspective and web vulnerability (SQLI).

In this README.md file I will explain what I learned and share with you some resources.

## Projects

* ### [Arachnida (First Task)](#arachnida)

## Arachnida (Fist Task)

### Scraping

I used Regex to scrape data. Regex is one of the most popular and good pattern-matching tool. If you don't have any idea about it you can click on [this](https://regexlearn.com/).

### What is EXIF?

EXIF (Exchangeable Image File) format includes videos and images. It stores a lot of information about the location where the photo was taken and the camera that was used.

* The location where the image was taken.
- At what altitude the image was captured?
* Was the cameraman moving at that time?
- Which way the cameraman was facing during the capture?
* Whether the image has been manipulated etc.

These metadata could be very important. Throughout history some criminial problems were solved with them. However EXIF format is easily changeable data, we can easily add some information or delete. Also some social media platforms remove these kinds of information when sharing images or photographs through WhatsApp or Facebook. Whereas others, Flickr does not.

**Note:** *If you don't want to lose any data when sharing images or photographs on WhatsApp or Facebook. Please compress them into a ZIP file.*

EXIF can include these metadata:

* Camera settings:
	* Model and Maker
	* Image orientation
	* Aperture
	* Shutter Speed
	* Focal length
	* Metering mode
	* ISO speed
* Image Metrics:
	* Pixel dimension
	* Resolution
	* Color space
	* File size
* Date and Time information:
	* Location Information
	* Thumbnail
	* Description
	* Copyright information etc.

*Please keep in mind. Scraping images from a website usually doesn't include EXIF data.*

# Resources

- [CS50 Cybersecurity from Harvard](https://youtu.be/9HOpanT0GRs?si=ZdNcDr-gx2_fYmco)
