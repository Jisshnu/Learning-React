App.js

import logo from './logo.svg';
import './App.css';

function what(){
  const names = ["Jodd","Gem","love"];
  const int = Math.floor(Math.random()*3);
  return names [int]
}
function App() {

  return (
    <div>
          <p>Jisshnu is {what()}</p>
    </div>
  );
}

export default App;
