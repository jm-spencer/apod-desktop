# apod-desktop
Script to set your Linux desktop wallpaper to the Astronomy Picture of the Day.

## Usage
Invoke the script on login using a method appropriate to your desktop manager

## How it works
This script scrapes the current [Astronomy Picture of the Day page](https://apod.nasa.gov/apod/astropix.html) for the image linked there, downloads the image, and sets it as your desktop wallpaper for a variety of Linux desktop managers.

Works on XFCE

Added additional logic to retry scraping in the event internet connection is not established immediately, as well as preventing APOD videos from being set to the wallpaper (and failing), instead just keeping the existing image.
