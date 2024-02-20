# React + Vite




App setup: 

main.js:
    - renders the App.jsx


App.jsx:
    - Router 
    - Layout is the main component that hosts all the children pages
    - States :
        const [cart, setCart] = useState([]);   
        const [currentProduct, setCurrentProduct] = useState(null);
        const [cartCount, setCartCount] = useState(null)
    
Layout.jsx:
    - Renders Footer, Outlet(Layout's children, based on url) and Footer



