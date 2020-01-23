---
##### shortDescription
Calls the [saveState](/api-reference/40%20SPA%20Framework/StateManager/3%20Methods/saveState().md '/Documentation/ApiReference/SPA_Framework/StateManager/Methods/#saveState') method of the application's [StateManager](/api-reference/40%20SPA%20Framework/StateManager '/Documentation/ApiReference/SPA_Framework/StateManager/') object.

---
By default, the application's state manager has only the navigation manager in the [collection of state sources](/api-reference/40%20SPA%20Framework/StateManager/3%20Methods/addStateSource(stateSource).md '/Documentation/ApiReference/SPA_Framework/StateManager/Methods/#addStateSourcestateSource'). So when calling this method, the navigation manager saves the current navigation history. Note that when the navigation system works in the [website](/concepts/40%20SPA%20Framework/3%20Navigation%20and%20Routing/6%20Navigation%20in%20Web%20Apps.md '/Documentation/Guide/SPA_Framework/Navigation_and_Routing/#Navigation_in_Web_Apps') mode, the navigation manager does nothing to save the state. In the [mobileApp](/Documentation/Guide/SPA_Framework/Navigation_and_Routing/#Navigation_in_Mobile_Apps) mode, the current [navigation stack](/concepts/40%20SPA%20Framework/3%20Navigation%20and%20Routing/5%20Navigation%20History%20in%20Mobile%20Apps.md '/Documentation/Guide/SPA_Framework/Navigation_and_Routing/#Navigation_History_in_Mobile_Apps') is saved to a *state storage*. In particular, the following information on the navigation stack is saved.

- Items in the current navigation stack
- The position of the displayed view in the current navigation stack