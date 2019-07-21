## explore-reactjs: 

### A SPA with ReactJs: 
  Meetup @Technogise, Saturday, July 20, 2019

#### React Elements:
Elements are the smallest building blocks of React apps; Its what you are see on the screen.

#### React Components: 
A react component is javasctipt class or function that rertuns React Element

#### React Props:

#### Why Components:
      - can split our UI into independent, reusable pieces and think of them in isolation
      - Declarative usage: We can use components in a declarative way
#### React.Fragment==> 
       - wrap inside a virtual html element which won't be render. Used when you does not want wrap element inside DOM element
#### Component:
       - Function Component: Stateless
       - Class Component: Stateful
#### States:
       - State is an observable object
	     - Do not change state directly
       
#### Lifecycle:
	     Series of methods that aee invoked in the different stages of components existence. React lifecycle contains following stages:
	        - Initialization
	        - Mounting
          - Unmounting
          - Updating
  1. Initiailization:
     In this we define the props and initial state of the component. It will be done in the constructor by setting, **this.state**  object.
  2. Mouting: After the initilization of the component, render method is called first time.  
     It will be done by:
	   ``` 
     componentWillMount() -
	     ==>render() is called in between
	   componentDidMount() -
     
  3. UnMounting: Final phase of the component. This is where the component gets unmounted from the DOM.
      It will be done by-->
	   ``` componentWillUnMount()   
  4. Updating: In this phase state or props are updated-->
     ``` It will be done by:
	        - Update by some user events
	        - Methods in this phase:
	            componentWillReceiveProps()
		          setState()
		          shouldComponentUpdate() ?--> boolean 
		          componentWillUpdate() --> Before the update
		                render()get called in between 
		          componentDidUpdate()  --> after the update
           

#### Creating Form Component:	

#### DOM, Virtual DOM, DIffing Algorithm:

#### React Hooks:

  - Effect hooks: Lets you perform side effects in your functional components
  
  - Custom Hooks: lets you extract components logic into reusable function
 
