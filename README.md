# 🎯 CSS Media Queries Template for All Screen Sizes

A clean and ready-to-use **responsive CSS media queries template** that helps developers quickly style their websites for different screen sizes — from giant desktop monitors to mobile phones.

> 📦 Perfect for Frontend Developers, Designers, and anyone who wants to build **responsive** websites faster.

---

## 📐 Screen Size Categories

| Category         | Example Device               | Max Width       |
|------------------|-------------------------------|-----------------|
| 🖥️ Large Screens   | iMac 27"                     | `> 1536px`         |
| 💻 Large Laptops   | MacBook Pro 14"              | `1536px`         |
| 💻 Small Laptops   | Dell XPS 13                  | `1280px`         |
| 📱 Tablets         | iPad Pro 11" (Portrait)      | `1024px`         |
| 📱 Phone Landscape | iPhone 8                     | `768px`          |
| 📱 Phone Portrait  | iPhone 8                     | `576px`          |

---

## 🧩 Template Code

```css
/* CSS Media Queries template for different screen sizes (with example device given for each screen size) */

/* Category: Large Screens
   Device: iMac (27-inch)
   Screen Size: 2560px
*/

/* --> For screen sizes greater than 1536px, comes the Large Screens category */

/* Category: Large Laptops
   Device: Macbook Pro (14-inch)
   Screen Size: 1512px
*/
@media (max-width: 1536px) {
    /* some styles */
}

/* Category: Small Laptops
   Device: Dell XPS 13 (13.4-inch)
   Screen Size: 1200px
*/
@media (max-width: 1280px) {
    /* some styles */
}

/* Category: Tablets
   Device: iPad Pro (11-inch)
   Screen Size: 834px - Potrait
*/
@media (max-width: 1024px) {
    /* some styles */
}

/* Category: Phone Landscape
   Device: iPhone 8 (4.7-inch)
   Screen Size: 667px
*/
@media (max-width: 768px) {
    /* some styles */
}

/* Category: Phone Potrait
   Device: iPhone 8 (4.7-inch)
   Screen Size: 667px
*/
@media (max-width: 576px) {
    /* some styles */
}
