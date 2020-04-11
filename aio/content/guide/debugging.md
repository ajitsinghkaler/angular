# Debugging angular apps

The Angular 9 Ivy runtime offers a new ng object for debugging Angular apps, when you run in Dev mode.

## Steps to follow to debug your app

1. Run your Angular 9 app
1. Open the Chrome developer tools
1. Select the component's element
1. Type the following code in your console

### Few of the ng features here

ng.getComponent(): function gets the component associated with the element. This works for us here because we passed an element that is a component. It would return null if the element is not a component (like a div).

