# degree_api typescript

![٢٠٢٣٠٢٢٧_٠٢١٥٣٦](https://user-images.githubusercontent.com/124408599/221446423-002c8beb-8f87-4314-9991-626fe7e8b695.png)

From ```Ali El0malki```

```
Official version 0.10.0 
```

## What is degree_api ?
Simple Functionality to REQUEST Data from any API in TypeScript.

## What is API?
API is the acronym for application programming interface — a software intermediary that allows two applications to talk to each other.
APIs are an accessible way to extract and share data within and across organizations.
APIs are all around us. 
Every time you use a rideshare app, send a mobile payment, or change the thermostat temperature from your phone, you’re using an API.

## Why use degree_api ?
one line to request api and catch errors, 
with high performance.

## What changes v0.10.0 ?
-- Changes in v0.10.0 :
- add New Method to REQUEST.
- add Paramas to Request URL.
- update performance.
- fixed some Bugs.
- Official Release!

## How i am add degree_api to my project?
add the package using npm!

```nodejs
npm i degree_api
```

## How use New Method ?

```typescript

// -- import degree_api -- //
import { NewGetRequest } from "degree_api";

// -- API URL [ Variable ] -- //
const URL_API = "API_KEY_HERE";

// -- Using NewGetRequest without [Param] in Project -- //
NewGetRequest(URL_API);

// -- Using NewGetRequest with [Param] in Project -- //
NewGetRequest(URL_API, <Your_Param>);


// -- Result -- //

// if => True => Congrats! Your response Here 👏 //
// if => False => The cause of the error will appear Here. //

```

## use Old Method ?

```typescript

// -- import degree_api -- //
import { OldGetRequest } from "degree_api";

// -- API URL [ Variable ] -- //
const URL_API = "API_KEY_HERE";

// -- Using OldGetRequest in Project -- //
OldGetRequest(URL_API);


// -- Result -- //

// if => True => Congrats! Your response Here 👏 //
// if => False => The cause of the error will appear Here. //

```
