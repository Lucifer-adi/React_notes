<h2>Babel</h2>
<p> transpiler , which convert high level language to low level<br>
ex= typescript to javaScript
</p><br>
<p>2. Web pack : removes extra code which is not in use and makes code short  helps reduce the runtime size.and Its main purpose is to make js code use in the browser.<br>
3. React : it js library not framework have concept of virtual dom which ,jsx writing,wite code in component for reusability and maintenance ,, “code onces and use multiple times”. And one way biding
4 component : are the block of code which easly combined and reuse <br>
5. Jsx = no need to appenchild(), create comp() method .<br>
6. State : it has set of key , value pair and tells how components render and behaves.<br>
Ex = usestate 👍The first element is the initialization value.
The second element is updation function
</p>
<h2>Controlled and uncontrolled comp</h2>

```javascript
import React, { useState } from 'react';

function ControlledInput() {
  const [value, setValue] = useState('');

  const handleChange = event => {
    setValue(event.target.value);
  };
  return (
    <input type="text" value={value} onChange={handleChange} />
  );
}

Uncontrolled comp : 
import React from 'react';

function UncontrolledInput() {
  const handleChange = event => {
    console.log(event.target.value);
  };

  return <input type="text" onChange={handleChange} />;}

  ```
  
  <
 
 
  
  

