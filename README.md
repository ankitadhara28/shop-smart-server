# Shop Smart Server  

Welcome to **Shop Smart Server**, an Express.js-based API developed by **ankitadhara28**. This project handles various e-commerce functionalities like loyalty points calculation, shipping cost estimation, tax calculation, discounts, and more. It is deployed on **Vercel** for easy scalability and seamless performance.  

---

## 🚀 **Project Features**  
- **Loyalty Points Calculation:** Calculates points based on purchase amount.  
- **Shipping Cost Estimation:** Estimates shipping costs using weight and distance.  
- **Delivery Time Estimation:** Calculates delivery time depending on the shipping method.  
- **Tax Calculation:** Calculates tax based on cart total.  
- **Membership Discount:** Applies membership discounts if applicable.  
- **Cart Total Calculation:** Adds new items to the current cart total.  

---

## 🛠️ **Technologies Used**  
- **Node.js:** JavaScript runtime environment.  
- **Express.js:** Lightweight and fast web framework for Node.js.  
- **CORS:** Enables cross-origin requests.  
- **Vercel:** A platform for serverless deployment.  

---

## ⚙️ **Setup Instructions**  
To run the project locally, follow these steps:  

1. **Clone the Repository:**  
   ```bash  
   git clone https://github.com/ankitadhara28/shop-smart-server.git  
2. **Navigate to the Project Directory:**
   cd shop-smart-server  
3. **Install dependencies:**
    npm install  
4. **Run the Server:**
    node index.js  
.

🌐 API Endpoints
Here’s a list of available endpoints with query parameters:

GET /loyalty-points?purchaseAmount=100

Calculates loyalty points based on the purchase amount.
GET /shipping-cost?weight=2&distance=50

Estimates the shipping cost using weight and distance.
GET /estimate-delivery?shippingMethod=standard&distance=100

Estimates the delivery time based on shipping method and distance.
GET /calculate-tax?cartTotal=200

Calculates tax for a given cart total.
GET /membership-discount?isMember=true&cartTotal=300

Applies a membership discount if the user is a member.
GET /cart-total?newItemPrice=50&cartTotal=200

Adds a new item’s price to the existing cart total.
📦 Deployment with Vercel
This project is deployed on Vercel with the following configuration to handle all incoming requests through index.js:
To deploy your own version:

1.Install the Vercel CLI.
2.Run the following command
  vercel  
3.Follow the instructions to deploy your project.

📚 Learn More
* Express.js Documentation
* Vercel Documentation

💬 Feedback & Contact
This project is proudly developed by ankitadhara28. Feel free to reach out if you have questions or suggestions. 😊
