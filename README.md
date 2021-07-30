# micro-frontends
A sample app to demo micro frontends in action

![](https://github.com/gauravbehere/micro-frontends/blob/master/images/mfeImg.png)

## File Structure
### Angular Components
There a single angular component "page-num". Displays the page number you are currently on.

### React Components
#### Pagination
Renders the controls for navigation.

#### Gallery
Fetches & renders images for the current page index.

### Container App
This is the container app (React) hosting all the micro frontends.

## Running the demo
1. In each of the micro frontends do an ```npm install``` & ```npm start```, this will make the microfront available as a service.
2. In the container component do an ```npm install``` & ```npm start```, this will make the container app available at
```http://localhost:5000```
