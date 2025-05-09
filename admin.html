<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Admin Panel - Inventory System</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 20px;
    }
    table {
      width: 100%;
      margin: 20px 0;
      border-collapse: collapse;
    }
    th, td {
      padding: 10px;
      border: 1px solid #ddd;
      text-align: center;
    }
    th {
      background-color: #f2f2f2;
    }
    footer {
      background-color: #f1f1f1;
      text-align: center;
      padding: 10px;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
    h2 {
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Admin Panel</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="products.html">Products</a>
      <a href="admin.html">Admin Panel</a>
    </nav>
  </header>

  <main class="container">
    <h2>Manage Inventory</h2>
    <table id="inventoryTable">
      <tr>
        <th>Product Name</th>
        <th>Stock Level</th>
        <th>Update Stock</th>
      </tr>
      <tr>
        <td>Smartphone A1</td>
        <td class="stock-level" data-product="Smartphone A1">50</td>
        <td><input type="number" value="50" class="stock-input" data-product="Smartphone A1" /></td>
      </tr>
      <tr>
        <td>Smartphone B2</td>
        <td class="stock-level" data-product="Smartphone B2">30</td>
        <td><input type="number" value="30" class="stock-input" data-product="Smartphone B2" /></td>
      </tr>
      <tr>
        <td>Laptop X3</td>
        <td class="stock-level" data-product="Laptop X3">20</td>
        <td><input type="number" value="20" class="stock-input" data-product="Laptop X3" /></td>
      </tr>
      <tr>
        <td>Laptop Y4</td>
        <td class="stock-level" data-product="Laptop Y4">15</td>
        <td><input type="number" value="15" class="stock-input" data-product="Laptop Y4" /></td>
      </tr>
      <tr>
        <td>Headphones Z5</td>
        <td class="stock-level" data-product="Headphones Z5">100</td>
        <td><input type="number" value="100" class="stock-input" data-product="Headphones Z5" /></td>
      </tr>
      <tr>
        <td>Bluetooth Speaker</td>
        <td class="stock-level" data-product="Bluetooth Speaker">75</td>
        <td><input type="number" value="75" class="stock-input" data-product="Bluetooth Speaker" /></td>
      </tr>
      <tr>
        <td>Smart Watch S6</td>
        <td class="stock-level" data-product="Smart Watch S6">40</td>
        <td><input type="number" value="40" class="stock-input" data-product="Smart Watch S6" /></td>
      </tr>
      <tr>
        <td>Tablet T7</td>
        <td class="stock-level" data-product="Tablet T7">60</td>
        <td><input type="number" value="60" class="stock-input" data-product="Tablet T7" /></td>
      </tr>
      <tr>
        <td>Camera C8</td>
        <td class="stock-level" data-product="Camera C8">10</td>
        <td><input type="number" value="10" class="stock-input" data-product="Camera C8" /></td>
      </tr>
      <tr>
        <td>Gaming Console G9</td>
        <td class="stock-level" data-product="Gaming Console G9">25</td>
        <td><input type="number" value="25" class="stock-input" data-product="Gaming Console G9" /></td>
      </tr>
    </table>
    
    <button id="updateStockButton">Update Stock</button>

    <!-- Orders Table Section -->
    <h2>Placed Orders</h2>
    <table id="ordersTable">
      <thead>
        <tr>
          <th>Customer Name</th>
          <th>Product</th>
          <th>Price</th>
          <th>Time</th>
        </tr>
      </thead>
      <tbody></tbody>
    </table>
  </main>

  <footer>
    <p>© 2025 Inventory Project by Ragul</p>
  </footer>

  <script>
    // Update stock button logic
    document.getElementById('updateStockButton').addEventListener('click', function () {
      const inputs = document.querySelectorAll('.stock-input');
      inputs.forEach(input => {
        const productId = input.getAttribute('data-product');
        const newStock = input.value;
        const stockCell = document.querySelector(`.stock-level[data-product="${productId}"]`);
        if (stockCell) {
          stockCell.innerText = newStock;
        }
        alert(`Stock for ${productId} updated to ${newStock}`);
      });
    });

    // Show placed orders from localStorage
    const orders = JSON.parse(localStorage.getItem("orders") || "[]");
    const ordersBody = document.querySelector("#ordersTable tbody");

    const productPrices = {
      "Smartphone A1": 20000,
      "Smartphone B2": 25000,
      "Laptop X3": 45000,
      "Laptop Y4": 50000,
      "Headphones Z5": 5000,
      "Bluetooth Speaker": 3500,
      "Smart Watch S6": 7000,
      "Tablet T7": 15000,
      "Camera C8": 30000,
      "Gaming Console G9": 22000
    };

    if (orders.length === 0) {
      ordersBody.innerHTML = "<tr><td colspan='4'>No orders placed yet.</td></tr>";
    } else {
      orders.forEach(order => {
        const row = document.createElement("tr");

        const name = document.createElement("td");
        name.textContent = order.customer || "Customer001";

        const product = document.createElement("td");
        product.textContent = order.product;

        const price = document.createElement("td");
        price.textContent = "₹" + (productPrices[order.product] || "N/A");

        const time = document.createElement("td");
        time.textContent = order.time;

        row.appendChild(name);
        row.appendChild(product);
        row.appendChild(price);
        row.appendChild(time);

        ordersBody.appendChild(row);
      });
    }
  </script>
</body>
</html>
