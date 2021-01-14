```jsx
Lets continue with Bootstrap elements to React. 

 When we search react bootstrap, then we see https://react-bootstrap.github.io/
 
 -- Optional: Before begin, you can play this song in background: https://www.youtube.com/watch?v=u9EFGKuxlMQ .
 
- So Lets begin.. 
  npm install react-bootstrap bootstrap or yarn add react-bootstrap bootstrap

- Then Components

  #### For example: Dropdown
    We converted our .html codes to components. So we need to prepare these html bootstrap codes for making components. Know we have this: 
      - Note! ~~ means delete it. ** means add it.
    
       <div class="project-name nowrap dropdown" data-component="Dropdown">
            <div data-component="selectProject">Frontend</div>
            <span class="i-btn icon-angle-down" role="button" id="dropdownMenuProject" ~~data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"~~ **data-component="Dropdown.Toggle**"></span>
            <div class="dropdown-menu dropdown-arrow dropdown-arrow-left" aria-labelledby="dropdownMenuProject" data-component="Dropdown.Menu">
                <a class="dropdown-item" href="#" data-component="Dropdown.Item">Action</a>
                <a class="dropdown-item" href="#" data-component="Dropdown.Item">Another action</a>
                <a class="dropdown-item" href="#" data-component="Dropdown.Item">Something else here</a>
            </div>
        </div>
    
    
    => to this. 
    
    <Dropdown>
      <Dropdown.Toggle variant="success" id="dropdown-basic">
        Dropdown Button
      </Dropdown.Toggle>

      <Dropdown.Menu>
        <Dropdown.Item href="#/action-1">Action</Dropdown.Item>
        <Dropdown.Item href="#/action-2">Another action</Dropdown.Item>
        <Dropdown.Item href="#/action-3">Something else</Dropdown.Item>
      </Dropdown.Menu>
    </Dropdown>
