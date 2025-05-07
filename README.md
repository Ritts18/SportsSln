## 🛠️ How to Run the Project

### 🔧 Requirements
- Visual Studio 2022 or newer
- .NET SDK 8.0 or later
- SQL Server LocalDB (or configured database)
- Internet connection (for Bootstrap CDN or local files)

### 📦 Setup Instructions

1. **Clone or Download** the repository.
2. Open the `.sln` file in Visual Studio.
3. Make sure your `wwwroot/css/site.css` exists and is linked in `_Layout.cshtml`.
4. Restore NuGet packages:
   - Go to **Tools > NuGet Package Manager > Manage NuGet Packages for Solution**
   - Restore all packages
5. Apply EF Core migrations (if needed):
   - Open **Package Manager Console**
   - Run:  
     ```
     Update-Database
     ```

6. Press **F5** or click **Start Debugging**.

---

## 🧑‍💻 User Manual

### Home Page
- Shows available sports products with image, name, price, and "Add to Cart" button.

### Navigation Menu
- Located on the left side. Click a **category** (e.g., Kayak, Ball) to filter products.

### Cart Summary
- Shown in the top-right header. Displays number of items in the cart and a link to view the full cart.

### Add to Cart
- Click the green **Add to Cart** button below a product to add it to your shopping cart.

### View Cart
- Click the **Cart Summary** in the header.
- Review items, update quantities, or proceed to checkout.

### Checkout
- Fill in your shipping details and submit the order.

---
