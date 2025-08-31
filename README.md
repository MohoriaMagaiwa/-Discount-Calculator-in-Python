# 🛒 Discount Calculator in Python

This is a simple but smart Python program that helps you figure out the **final price** of an item after applying a discount.  
It uses a function named `calculate_discount(price, discount_percent)`.

---

## ✨ How It Works
- You enter the **original price** of an item 💵
- You enter the **discount percentage** 🎯
- If the discount is **20% or more**, the discount is applied ✅
- If it’s **less than 20%**, the price stays the same ❌

---

## 🔧 Function Used

```python
def calculate_discount(price, discount_percent):
    if discount_percent >= 20:
        return price - (price * discount_percent / 100)
    else:
        return price

