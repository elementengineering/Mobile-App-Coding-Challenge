# Coding Challenge
**Thank you for taking part in our Coding Challenge for our Native App Developer Role.** 

Please see the requirements below. When finished, please contact us with your submission and be prepared to review the code with us.

# Objectives
- Create either an iOS (must be in SwiftUI) or Android (must be in Kotlin) single-view app to display geographical information downloaded from a given URL. The URL will be provided to you. 

# Minimum Criteria
- Display the data as annotations on an Apple/Google map view.
- Display the data and time in the device's local timezone.
- Able to filter the data by the fields transport type, express and topup.
- Demonstrate the uses of MVVM design pattern.
- Demonstrate unit testing of model and view-model.
- It is your decision to design the UI, the screenshots below are just for example only.

# Bonus
- Online repostory, e.g. GitHub, GitLab, BitBucket & etc.
- Build and test using Fastlane.
- UI tests.
- UI/UX design, add whatever user-friendly features as you want, e.g. graphics, animations.
- Network error handling.

## Examples
### Android
<img src="screenshots/android/map_marker.png" width="250">

### iOS
<img src="screenshots/ios/map_marker.png" width="250">

# Data Sample
## Description
- typeId: Type of tansport, 0 = train, 1 = tram
- deapartureTime: Next departure data and time in GMT
- name: Transport station name,
- latitude: latitude of the GPS coordinate
- longitude: longitude of the GPS coordinate
- isExpress: true = Express, false = Normal
- hasMyKiTopUp: true = Myki topUp facility available in the station, false = no topup facility
- route: Next departure route number
```json
[
    {
        "typeId": 0,
        "departureTime": "2021-07-03T09:10:00.000Z",
        "name": "Flinders",
        "latitude": -37.8181755,
        "longitude": 144.9661256 },
    {
        "typeId": 0,
        "departureTime": "2021-07-03T14:30:00.000Z",
        "name": "Flinders",
        "latitude": -37.8181755,
        "longitude": 144.9661256,
        "isExpress": true },
    {
        "typeId": 0,
        "departureTime": "2021-07-04T10:15:00.000Z",
        "name": "North Melbourne",
        "latitude": -37.8068073,
        "longitude": 144.9404548,
        "isExpress": false },
    {
        "typeId": 0,
        "departureTime": "2021-07-04T15:35:00.000Z",
        "name": "Upfield",
        "latitude": -37.5856691,
        "longitude": 145.2270446,
        "isExpress": true },
    {
        "typeId": 0,
        "departureTime": "2021-07-05T11:20:00.000Z",
        "name": "Glen Waverley",
        "latitude": -37.8794913,
        "longitude": 145.1598501,
        "isExpress": false },
    {
        "typeId": 0,
        "departureTime": "2021-07-05T16:40:00.000Z",
        "name": "Ringwood",
        "latitude": -37.8153668,
        "longitude": 145.2269614,
        "isExpress": false },
    {
        "typeId": 0,
        "departureTime": "2021-07-06T12:45:00.000Z",
        "name": "Frankston",
        "latitude": -38.1429773,
        "longitude": 145.1238214,
        "isExpress": true },
    {
        "typeId": 0,
        "departureTime": "2021-07-06T17:45:00.000Z",
        "name": "Werribee",
        "latitude": -37.8985846,
        "longitude": 144.6590184,
        "isExpress": true },
    {
        "typeId": 1,
        "departureTime": "2021-07-07T13:50:00.000Z",
        "route": "624",
        "name": "Queen Victoria Market",
        "latitude": -37.806718,
        "longitude": 144.9574589,
        "hasMyKiTopUp": true },
    {
        "typeId": 1,
        "departureTime": "2021-07-07T18:50:00.000Z",
        "route": "625",
        "name": "Carlton Gardens",
        "latitude": -37.8049684,
        "longitude": 144.9572112,
        "hasMyKiTopUp": true },
    {
        "typeId": 1,
        "departureTime": "2021-07-08T14:55:00.000Z",
        "route": "820",
        "name": "Chadstone Shopping Centre",
        "latitude": -37.8862515,
        "longitude": 145.0807788,
        "hasMyKiTopUp": true },
    {
        "typeId": 1,
        "departureTime": "2021-07-09T19:55:00.000Z",
        "route": "543",
        "name": "Monash University",
        "latitude": -37.8771484,
        "longitude": 145.0427026,
        "hasMyKiTopUp": true },
    {
        "typeId": 1,
        "departureTime": "2021-07-08T16:00:00.000Z",
        "route": "701",
        "name": "Brighton Beach",
        "latitude": -37.9265405,
        "longitude": 144.9868176,
        "hasMyKiTopUp": false
    }
]
```

© 2021 Element Engineering Australia Pty Ltd
