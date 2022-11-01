
![App Brewery Banner](Documentation/AppBreweryBanner.png)

## About this app

It is a beautiful, dark-mode enabled weather app. You are be able to check the weather for the current location based on the GPS data from the iPhone as well as by searching for a city manually. 

## What we have accomplished

* How to create a dark-mode enabled app.
* How to use vector images as image assets.
* Learn to use the UITextField to get user input. 
* Learn about the delegate pattern.
* Swift protocols and extensions. 
* Swift guard keyword. 
* Swift computed properties.
* Swift closures and completion handlers.
* Learn to use URLSession to network and make HTTP requests.
* Parse JSON with the native Encodable and Decodable protocols. 
* Learn to use Grand Central Dispatch to fetch the main thread.
* Learn to use Core Location to get the current location from the phone GPS. 

### Condition Codes
```
switch conditionID {
        case 200...232:
            return "cloud.bolt"
        case 300...321:
            return "cloud.drizzle"
        case 500...531:
            return "cloud.rain"
        case 600...622:
            return "cloud.snow"
        case 701...781:
            return "cloud.fog"
        case 800:
            return "sun.max"
        case 801...804:
            return "cloud.bolt"
        default:
            return "cloud"
        }
```

### Light Mode Example

<img width="387" alt="lightMode" src="https://user-images.githubusercontent.com/32853291/199281812-80cb4bc4-9fb6-48cb-9a93-de9213e9c06f.png">


### Dark Mode Example

<img width="386" alt="darkMode" src="https://user-images.githubusercontent.com/32853291/199281839-c4d94312-873d-409c-866d-7fc698844806.png">


>This is a companion project to The App Brewery's Complete App Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)
