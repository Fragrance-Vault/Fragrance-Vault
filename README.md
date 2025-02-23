<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Fragrance Vault - Shop perfumes and decants online. Quality products delivered to your door.">
    <title>Fragrance Vault</title>
</head>
<body style="font-family: Arial, sans-serif; background-color: #f4f4f4; margin: 0; padding: 0;">

    <!-- Header Section -->
    <header style="background-color: #333; color: white; text-align: center; padding: 20px;">
        <h1>Fragrance Vault</h1>
        <p>Discover Timeless Perfumes & Decants</p>
    </header>

    <!-- Navigation Menu -->
    <nav style="background-color: #444; text-align: center; padding: 10px;">
        <a href="#products" style="color: white; margin: 0 15px; text-decoration: none; font-weight: bold;">Products</a>
        <a href="#feedback" style="color: white; margin: 0 15px; text-decoration: none; font-weight: bold;">Feedback</a>
        <a href="#order" style="color: white; margin: 0 15px; text-decoration: none; font-weight: bold;">Order Now</a>
    </nav>

    <!-- Products Section -->
    <section id="products" style="padding: 20px; max-width: 1200px; margin: 0 auto;">
        <h2>Our Perfumes & Decants</h2>
        <div style="display: flex; gap: 20px; flex-wrap: wrap; justify-content: center;">
            <!-- Product 1: Azzaro The Most Wanted Parfum -->
            <div style="background-color: white; padding: 15px; text-align: center; border-radius: 8px; width: 250px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
                <img src="Azzaro The Most Wanted Parfum.jpg" alt="Azzaro The Most Wanted Parfum" style="width: 100%; border-radius: 8px;">
                <h3>Azzaro The Most Wanted Parfum</h3>
                <p>A This men’s cologne combines irresistible toffee and bourbon vanilla, with spicy red ginger and woody accords, creating a fiery and magnetic fragrance that captures burning energy.</p>
                <p>Key Notes: Red Ginger, Incandescent Wood, Bourbon Vanilla.</p>
                <div>
                    <label for="size1" style="font-weight: bold;">Select Size:</label>
                    <select id="size1" onchange="updatePrice('price1', this)">
                        <option value="5ml">5ml - LKR3000</option>
                        <option value="10ml">10ml - LKR5500</option>
                    </select>
                </div>
                <p><strong>Price:</strong> <span id="price1">LKR3000</span></p>
                <a href="https://wa.me/94763701230?text=I%20want%20to%20order%20Azzaro%20No.%20Most%20in%205ml" style="display: inline-block; background-color: #25d366; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px;">Order via WhatsApp</a>
            </div>

            <!-- Product 2: Dior Sauvage -->
            <div style="background-color: white; padding: 15px; text-align: center; border-radius: 8px; width: 250px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
                <img src="Dior Sauvage.jpg" alt="Dior Sauvage" style="width: 100%; border-radius: 8px;">
                <h3>Dior Sauvage</h3>
                <p>Dior Sauvage Eau De Parfum embodies understated confidence and strength, inspired by cool desert nights. Its blend of spicy notes, fresh bergamot, sensual leather, woody Ambroxan, and smoky vanilla creates a captivating, long-lasting fragrance.</p>
                <div>
                    <label for="size2" style="font-weight: bold;">Select Size:</label>
                    <select id="size2" onchange="updatePrice('price2', this)">
                        <option value="5ml">5ml - LKR3900</option>
                        <option value="10ml">10ml - LKR6900</option>
                    </select>
                </div>
                <p><strong>Price:</strong> <span id="price2">LKR3900</span></p>
                <a href="https://wa.me/94763701230?text=I%20want%20to%20order%20Dior%20Sauvage%20in%205ml" style="display: inline-block; background-color: #25d366; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px;">Order via WhatsApp</a>
            </div>

            <!-- Product 3: Rayhaan Crimson -->
            <div style="background-color: white; padding: 15px; text-align: center; border-radius: 8px; width: 250px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
                <img src="Rayhaan Crimson.jpg" alt="Rayhaan Crimson" style="width: 100%; border-radius: 8px;">
                <h3>Rayhaan Crimson</h3>
                <p>A Bold Expression of Power and Elegance. A fragrance that commands attention, Rayhaan Crimson exudes warmth, depth, and undeniable allure. Its rich, spicy character unfolds into a refined blend of sensuality and strength, leaving behind an irresistible, long-lasting trail.</p>
                <div>
                    <label for="size3" style="font-weight: bold;">Select Size:</label>
                    <select id="size3" onchange="updatePrice('price3', this)">
                        <option value="5ml">5ml - LKR1500</option>
                        <option value="10ml">10ml - LKR2500</option>
                    </select>
                </div>
                <p><strong>Price:</strong> <span id="price3">LKR1500</span></p>
                <a href="https://wa.me/94763701230?text=I%20want%20to%20order%20Rayhaan%20Crimson%20in%205ml" style="display: inline-block; background-color: #25d366; color: white; padding: 10px 15px; text-decoration: none; border-radius: 5px;">Order via WhatsApp</a>
            </div>
        </div>
    </section>

    <!-- Customer Feedback Section -->
    <section id="feedback" style="background-color: white; padding: 20px; margin: 20px auto; width: 80%; max-width: 600px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
        <h2>Customer Feedback</h2>
        <!-- Feedback Form -->
        <form id="feedback-form" onsubmit="submitFeedback(event)">
            <label for="name" style="display: block; font-weight: bold;">Your Name:</label>
            <input type="text" id="name" name="name" required style="width: 100%; padding: 10px; margin: 10px 0; border-radius: 5px; border: 1px solid #ccc;">

            <label for="email" style="display: block; font-weight: bold;">Your Email:</label>
            <input type="email" id="email" name="email" required style="width: 100%; padding: 10px; margin: 10px 0; border-radius: 5px; border: 1px solid #ccc;">

            <label for="message" style="display: block; font-weight: bold;">Your Feedback:</label>
            <textarea id="message" name="message" rows="4" required style="width: 100%; padding: 10px; margin: 10px 0; border-radius: 5px; border: 1px solid #ccc;"></textarea>

            <button type="submit" style="background-color: #25d366; color: white; padding: 10px 15px; border: none; border-radius: 5px; cursor: pointer;">Submit Feedback</button>
        </form>

        <h3>Recent Feedbacks:</h3>
        <ul id="feedback-list" class="feedback-list">
            <!-- User feedback will be appended here -->
        </ul>
    </section>

    <!-- Order Section -->
    <section id="order" style="text-align: center; padding: 40px;">
        <h2>Place an Order</h2>
        <p>If you're ready to make a purchase, click below to contact us via WhatsApp.</p>
        <a href="https://wa.me/94763701230?text=I%20want%20to%20place%20an%20order" style="background-color: #25d366; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">Order via WhatsApp</a>
    </section>

    <!-- Footer Section -->
    <footer style="background-color: #333; color: white; text-align: center; padding: 20px;">
        <p>&copy; 2025 Fragrance Vault. All rights reserved.</p>
        <p>Contact us: <a href="mailto:fragrance.vault18@gmail.com" style="color: white; text-decoration: none;">fragrance.vault18@gmail.com</a></p>
        <p>Call us: <a href="tel:+94763701230" style="color: white; text-decoration: none;">0763701230</a></p>
        <p>Follow us on Instagram: <a href="https://www.instagram.com/fragrance_vault__" target="_blank" style="color: white; text-decoration: none;">@fragrance_vault__</a></p>
    </footer>

    <script>
        // Function to update the price based on the selected decant size
        function updatePrice(priceId, selectElement) {
            const selectedSize = selectElement.value;
            let priceText = '';

            // Update price based on selected size and priceId
            if (selectedSize === '5ml') {
                if (priceId === 'price1') {
                    priceText = 'LKR3000';
                } else if (priceId === 'price2') {
                    priceText = 'LKR3900';
                } else if (priceId === 'price3') {
                    priceText = 'LKR1500';
                }
            } else if (selectedSize === '10ml') {
                if (priceId === 'price1') {
                    priceText = 'LKR5500';
                } else if (priceId === 'price2') {
                    priceText = 'LKR6900';
                } else if (priceId === 'price3') {
                    priceText = 'LKR2500';
                }
            }

            // Update the price displayed on the page
            document.getElementById(priceId).textContent = priceText;
        }

        // Function to submit feedback
        function submitFeedback(event) {
            event.preventDefault();

            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const message = document.getElementById('message').value;

            // Append feedback to the list
            const feedbackList = document.getElementById('feedback-list');
            const feedbackItem = document.createElement('li');
            feedbackItem.innerHTML = `<strong>${name}</strong> (${email}):<br>${message}`;
            feedbackList.appendChild(feedbackItem);

            // Clear the form
            document.getElementById('feedback-form').reset();
        }
    </script>
</body>
</html>
