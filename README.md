# Automated Food Warehouse Robot

## 📝 Description
This project showcases a **robotic system** designed to automate the process of transporting items from a food warehouse **without human intervention**. The robot consists of a mobile base, a robotic arm, and a shelf representing the storage area.

## 🧠 Algorithm
1. Robot starts in standby mode.
2. When a request is received:
   - The arm moves toward the shelf.
   - The gripper aligns with the target product.
   - The gripper closes to grab the item.
   - The arm retracts and places the item on the mobile base.
3. The robot navigates to the delivery point autonomously.
4. It places the item at the drop-off zone.
5. Returns to standby position.

## 🧱 Components Used
- **Mobile base (dark gray):** Represents the moving platform.
- **Robotic arm (light gray + red gripper):** Picks and places items.
- **Warehouse shelf (brown):** Storage for products.
- **Product (red cube):** Sample item for pickup.
- **Tinkercad shapes:** Box, cylinder, grouped components.

## 📐 Working Envelope
- The arm operates within a defined rectangular zone:
  - **Horizontal reach:** from base to shelf (approx. 100 mm)
  - **Vertical reach:** shelf height (approx. 50–70 mm)

## 📸 Project Preview
A snapshot of the robot grabbing a product from the shelf is included in this repo as `design.png`.

## 📁 Files in this Repository
- `README.md` → Project description and steps
- `algorithm.txt` → Written algorithm steps
- `components.txt` → List of used components
- `design.png` → Screenshot of the final robot in Tinkercad