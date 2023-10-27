
# Testing 

---

```javascript  
import React, { useState } from 'react';
import Calendar from 'react-calendar';
import 'react-calendar/dist/Calendar.css'
export default function Component() {
  const [value, onChange] = useState(new Date());
  return (
    <div> 
      <Calendar onChange={onChange} value={value} />
    </div>
  );
}
  
```

  
[Open Storybook Canvas](https://6195b518b76f57003aa69b4c-ynczzfqqyq.chromatic.com?path=%2Fstory%2Fbuttons-buttongroup--primary-color&addons=1&stories=0&panel=true&nav=false)  


compo

```javascript  
import React from 'react';
export default function Button(props) {
 return (
   <button>
     Click me!
   </button>
 );
}  
```

  
**Token Group Typography**:    
H1: Advent Pro 700 57px  
H2: Advent Pro 700 43px  
H3: Advent Pro 700 32px  
H4: Advent Pro 700 24px  
H5: Advent Pro 700 21px  
Large Lead: Advent Pro 400 24px  
Medium Lead: Advent Pro 400 21px  
Button Label: Advent Pro 400 21px, upper  
Paragraph: Advent Pro 400 18px  
Small Paragraph: Advent Pro 400 16px  
Tiny Paragraph: Advent Pro 400 12px  
Sale: Advent Pro 700 24px, upper  
impact label: Impact Label 400 13px  
poppins: Poppins 400 13px  
Token #1: Inter regular 14px  


  
  


  
![Frame 1](https://studio-assets.supernova.io/design-systems/95692/d271759d-f22e-4f24-9af8-a35a68f74847.png)  
Frame 1  
