# RealFunGi

##### By Adams Wonderboy

### It is a description of dadsaysjoke, a stand-up platform that enables users freely view dad jokes, relieving them from stress and / relax

## Table of Content

- [RealFunGi](#realfungi)
        - [By Adams Wonderboy](#by-adams-wonderboy)
    - [It is a description of dadsaysjoke, a stand-up platform that enables users freely view dad jokes, relieving them from stress and / relax](#it-is-a-description-of-dadsaysjoke-a-stand-up-platform-that-enables-users-freely-view-dad-jokes-relieving-them-from-stress-and--relax)
  - [Table of Content](#table-of-content)
  - [Description](#description)
  - [Overview](#overview)
  - [Installation](#installation)
    - [Run the Project](#run-the-project)
  - [Requirements](#requirements)
  - [Technology Used](#technology-used)

## Description

<p>This is  a stand-up based platform of random dadjokes that are groan-worthy, pun-laden, can't-help-but-laugh type of humor that dads are best at delivering. Put these so-bad-they're-good best dad jokes of all time to use and put a smile on somebody's face.</p>

## Overview

![My Image](/assets/images/readmetop.png)

![My Image](/assets/images/readmelocal.png)

## Installation

- Open the project using IDE of preference
  
- On the root folder, locate index.html file and run it through the liveserver.
- This should open in your default browser in case you are using VS Code :)
- Install your own `json-server` to run local calls via `npm -i json-server`.
- Use `npm -i -g json-server` to install the server on a global scope.

### Run the Project

- Public API calls
  
```md
DOMContentLoaded is in syn, the API call is made immediately the site is loaded.

Since we are limited to QUOTAS per day, kindly note the API can only make 10 requests a day.

RELOAD WHEN NEEDED!!
```

- Local API calls

```md
N/B: This part will run only when the public API Quota limit is exceeded or the user invokes the localHost() function via the browser console. 

Make sure your liverserver is running to display contents of index.html file in the root directory.

Follow the instructions below to fireup json-server
```

Start the JSON server

```json
json-server --watch db.json --routes routes.json
```

## Requirements

- Access it via a computer or laptop

- An access to the Internet for the Public API consumption

[Go Back to the top](#table-of-content)

## Technology Used

- HTML - which was used to build the structure of the pages.

- CSS - which was used to style the pages.

- JS - used for creating functions and making the page interactive.
  
- Fetch API - allows to asynchronously request for a resource.

[Go Back to the top](#table-of-content)

MIT License

Copyright (c) 2022 moringawonder

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
