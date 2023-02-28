<template>
  <main class="wrapper">
    <h1>Past Orders</h1>

    <table class="product-table">
      <thead>
        <tr>
          <th><span class="sr-only">Product Image</span></th>
          <th>Product</th>
          <th>Price</th>
          <th>Quantity</th>
          <th>Total</th>
          <th><span class="sr-only">Actions</span></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><i class="icofont-carrot icofont-4x"></i></td>
          <td>Carrot</td>
          <td>$1.00</td>
          <td>1</td>
          <td>$1.00</td>
          <td><button class="btn btn-dark">Add</button></td>
        </tr>
        <tr>
          <td><i class="icofont-banana icofont-4x"></i></td>
          <td>Banana</td>
          <td>$0.50</td>
          <td>10</td>
          <td>$5.00</td>
          <td><button class="btn btn-dark">Add</button></td>
        </tr>
      </tbody>
    </table>
  </main>
</template>
