# 2400032821skillnsemExam1
insem exam code
import React from "react";

function Card(props) {
  const style = {
    border: "2px solid black",
    padding: "15px",
    margin: "10px",
    borderRadius: "8px",
    boxShadow: "2px 2px 5px gray"
  };
  return <div style={style}>{props.children}</div>;
}

export default Card;
2. App.js
jsx
Copy code
import React from "react";
import Card from "./Card";

function App() {
  return (
    <div>
      <Card>
        <h2>Hello World</h2>
        <p>This is inside the Card component.</p>
      </Card>

      <Card>
        <button>Click Me</button>
      </Card>
    </div>
  );
}

export default App;
