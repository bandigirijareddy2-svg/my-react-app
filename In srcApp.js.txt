// In src/App.js
function App() {
return (
<div className="App">
<header className="App-header">
<nav style={{ backgroundColor: '#333', padding: '10px', color: 'white' }}>
<a href="#" style={{ color: 'white', margin: '0 10px' }}>Home</a>
<a href="#" style={{ color: 'white', margin: '0 10px' }}>About</a>
<a href="#" style={{ color: 'white', margin: '0 10px' }}>Contact</a>
</nav>
<img src={logo} className="App-logo" alt="logo" />
<p>
Edit <code>src/App.js</code> and save to reload.
</p>
<a
className="App-link"
href="https://reactjs.org"
target="_blank"
rel="noopener noreferrer"
>
Learn React
</a>
</header>
</div>
);
}