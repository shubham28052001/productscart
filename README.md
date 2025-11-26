# ProductsCart 🛒

Ye ek simple “product listing + shopping cart” web‑app hai jo **HTML, CSS, Bootstrap & plain JavaScript** use karke banaya gaya hai.  

## 🌐 Live Demo

[Click here to view the live project](https://shubham28052001.github.io/productscart/) 
## ✅ Features

- Products ko fetch karta hai external API se (dummy JSON).  
- Products ko grid me display karta hai with carousel images.  
- Products ke saath title, price, discount, stock, rating dikhata hai.  
- Sorting: Price low‑to‑high, high‑to‑low; Title A–Z / Z–A.  
- Search functionality — user text dal ke products filter kar sakta hai.  
- Add to Cart: Products cart me add karo, aur cart panel me dekh sakte ho.  
- Cart operations:
  - Quantity increase / decrease  
  - Remove item  
  - Total price calculation  
  - Cart persistence using sessionStorage — page refresh hone par bhi cart data barkarar rahta hai  
- Responsive layout — Desktop + Tablet + Mobile dono ke liye compatible.  
- Dark theme UI + clean styling.  

## 📁 Project Structure


## 🛠️ How to Use / Run Locally

1. Simply **open `index.html`** in your browser (no server required, static site).  
2. Products load automatically from the API.  
3. Use the **Sort by Price / A–Z dropdown** to sort products.  
4. Use the **search bar** to find products by title, category or brand.  
5. Click **“Add to cart”** on any product — cart panel opens from top.  
6. In cart panel you can:  
   - Increase / decrease quantity  
   - Remove items  
   - See total price  
7. Cart is saved in `sessionStorage`, so **page refresh** par bhi cart data nahi lose hota.  

## 🧑‍💻 Tech / Tools Used

- HTML5  
- CSS3 (with responsive media‑queries)  
- Bootstrap (for carousel + some UI defaults)  
- Vanilla JavaScript (DOM manipulation, fetch API, event handling)  

## 💡 Potential Improvements / Future Enhancements

- Persist cart using `localStorage` instead of `sessionStorage`, taaki browser close hone ke baad bhi data rahe.  
- Add a “Cart Icon + Item Count” in header for quick cart overview.  
- Implement a product detail page/modal on product click.  
- Lazy‑load images for better performance on slower connections.  
- Filtering by category, price range, rating etc. ek advanced filter panel bana sakte hain.  
- “Wishlist / Favorites” feature add kar sakte hain.  
- Dark/light mode toggle.  
- Code modularization — separate JS files for cart logic, UI, data fetching etc.  

## 📬 Contact / Feedback

Agar koi bug mile ya suggestion ho, feel free to open issue / pull‑request (agar GitHub repo link ho).  
