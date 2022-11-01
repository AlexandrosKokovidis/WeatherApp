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

<img width="404" alt="LightMode" src="https://user-images.githubusercontent.com/32853291/199283388-fe18bf35-275c-4c4f-a763-e2e093d16b29.png">


### Dark Mode Example

<img width="401" alt="DarkMode" src="https://user-images.githubusercontent.com/32853291/199283363-d73dd2fd-1fbf-407f-9e27-c568e3d77e08.png">

### Details Info

<img width="396" alt="DetailsInfo" src="https://user-images.githubusercontent.com/32853291/199284918-cb2f6423-4a9a-4fdc-b0bd-e60332d66483.png">

1) GPS option for current user location.
2) Variety of icons, considering the weather status.
3) Variety of icons, considering the temperature's value.


>This is a companion project to The App Brewery's Complete App Development Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)
