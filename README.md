##### Simple onclick, onChange events.
##### const [count, setCount] = useState(0);

#### Updating state based on current state:-
###### const handleIncrease = () => {
###### setCount(count + 1); // 0+1
###### setCount(count + 1); // 0+1
###### setCount(count + 1); // 0+1
######  };
###### Output is 1

#### Updating state based on previous state:-
###### const handleIncrease = () => {
###### setCount((count)=>count+1); // 0+1
###### setCount((count)=>count+1); // 1+1
###### setCount((count)=>count+1); // 2+1
######  };
###### Output is 3
