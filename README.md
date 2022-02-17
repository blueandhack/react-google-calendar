# React Google Calendar

![npm (scoped)](https://img.shields.io/npm/v/@chervint/react-google-calendar) [![Build Status](https://api.travis-ci.com/chervintani/react-google-calendar.svg?branch=master)](https://app.travis-ci.com/github/chervintani/react-google-calendar)   
  
This is a forked repository from [ericz1803/react-google-calendar](https://github.com/ericz1803/react-google-calendar)

See it in action [here](https://chervint.github.io/react-test-calendar/) or try it yourself in CodeSandbox [here](https://codesandbox.io/s/purple-architecture-hp8p8).

Features added:
- Calendar events in a day is sorted
- "Copy to Calendar" to "Go to Calendar" to go to specific date on click
- Added `selectedMonthYear` to select specific month in the calendar

### Properties
| Parameter             | Type             | Description                                                                     |
|-----------------------|------------------|---------------------------------------------------------------------------------|
| `apiKey`              | string           | google api key (required)                                                       |
| `calendars`           | array of objects | google calendar id and display color (required)                                 |
| `styles`              | object           | styles (optional, see more below)                                               |
| `showArrow`           | boolean          | shows arrow for events that span multiple months (optional, defaults to `true`) |
| `showFooter`          | boolean          | whether or not to show footer (optional, defaults to `true`)                    |
| `language`            | string           | Available options : 'ES', 'PT', 'FR', 'SL' default: 'EN'                        |
| `selectedMonthYear`   | moment(date)     | select specific month in the calendar (optional)                                |

### More Information

For more information of this library, please visit the original version [ericz1803/react-google-calendar](https://github.com/ericz1803/react-google-calendar).

## License
MIT License
