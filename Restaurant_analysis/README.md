# 🍽️ From Raw Data to Delicious Insights — My First Power BI Dashboard Project

Hi there! 👋

I recently started exploring Power BI, and this post is about my **very first Power BI project** — an experience that introduced me to the world of dashboards, data modeling, and telling stories with visuals. If you're new to data analysis or Power BI, this might just give you the push to start your own journey too!

---

## 📦 Where It All Started...

The dataset I worked on was given to me by one of my college professors. The idea was simple:  
> "Take this restaurant data and explore it. Visualize what you can."

There was no fixed outcome or strict rules — which made it even more exciting. This was a chance to really explore Power BI, learn how to connect tables, clean data, and experiment with visuals. I call this my **exploratory project** — and it helped me understand how powerful Power BI really is.

---

## 🧹 Step 1: Cleaning the Chaos

The raw data included multiple tables:
- A **restaurant table** with restaurant name, code, and type
- An **item table** with food names and categories
- A **customer table** with customer names, IDs, and types like "Gold", "Regular"
- And an **order table** that tied everything together with order details, quantity, delivery status, and payment method

There were some typical data issues — for example:
- Customer types were written inconsistently: `gold`, `g`, `reular`, `r` — I fixed these to just `Gold` and `Regular`.
- Some quantity fields were null, so I replaced those with `0`.
- The column names between tables didn’t match exactly (e.g., `item code` vs `fooditem`), so I manually established the relationship between them.

By the end of it, I had a nice, clean dataset ready for building the dashboard.

---

## 📊 Step 2: Building the Dashboard

Now the fun part!

I started dragging in visuals, and along the way, I learned a LOT:
- How to use **tree maps** for showing food items ordered across different restaurants
- How to create **KPIs** for total orders, total quantity, and number of customers
- How to use **slicers** (filters) for restaurant types to make the dashboard more interactive

Here’s what my final dashboard included:
- 📌 **Top Restaurants** by number of orders
- 🍛 **Most Popular Food Items** (Samosa won! 🥇)
- 📅 **Top 10 Days** with the most orders
- 🧍‍♀️ Customer segmentation: Gold vs Regular
- 🏢 A filter for Restaurant Type (to focus the view)
- 💬 A **Q&A box** where I could literally type questions like "Count food types" and get auto-generated answers from the data — very cool!

I even added tooltips and formatted my charts to make the whole experience smooth and readable.

---

## 🔍 Step 3: What I Learned from the Dashboard

By looking at the dashboard, I could answer several questions — and this is where I felt like a real analyst:

- **Which restaurants were most popular?**  
  ➝ *Bukhara*, *Saravana Bhavan*, and *Indian Accent* topped the list.

- **What food items were ordered the most?**  
  ➝ *Samosa*, *Butter Chicken*, and *Chole Bhature* were top favorites.

- **Which days had peak orders?**  
  ➝ Around the middle and end of the month, possibly weekends or special dates.

- **Customer types:**  
  ➝ Gold members made up 60% of the orders, showing that loyalty programs really do work!

This was also my first time understanding how filters and slicers can really help **business teams** explore data their own way.

---

## 💡 What Power BI Taught Me

This project wasn't just about charts and numbers. It taught me how to:
- Ask the right questions from data
- Connect multiple tables with relationships
- Handle messy real-world data
- Build something visually clear and interactive
- And most importantly, tell a story through data

I loved how **non-technical users** (like managers or restaurant owners) could just look at this dashboard and immediately understand what's happening in their business.

---

## 👋 Wrapping Up

If you're someone who’s just starting out — my advice is:
> Don’t worry about being perfect. Start with the basics, explore your data, and just build something! 🚀

Power BI makes it easy to experiment, and this project really helped me unlock its potential.

---

**Thanks for reading!**  
Let me know what you think — and if you’ve built something similar, I’d love to check it out. 🙌


