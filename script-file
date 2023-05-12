// Function to show/hide shipping method based on the entered zip code
function showHideShippingMethod() {
  // Get the shipping method element
  var shippingMethodElement = document.getElementById('shipping-method'); // Replace 'shipping-method' with the ID or class of your shipping method element

  // Get the entered zip code
  var enteredZipCode = document.getElementById('zip-code-input').value; // Replace 'zip-code-input' with the actual ID or class of your zip code input field

  // Check if the entered zip code matches the allowed zip code
  var shouldShowShippingMethod = (enteredZipCode === '90404');

  // Show/hide the shipping method
  if (shouldShowShippingMethod) {
    shippingMethodElement.style.display = 'block';
  } else {
    shippingMethodElement.style.display = 'none';
  }
}

// Call the function when the page loads
document.addEventListener('DOMContentLoaded', function() {
  // Call the function on page load
  showHideShippingMethod();

  // Add an event listener to the zip code input field
  var zipCodeInput = document.getElementById('zip-code-input'); // Replace 'zip-code-input' with the actual ID or class of your zip code input field
  zipCodeInput.addEventListener('input', showHideShippingMethod);
});
