# Pricing Table

A responsive pricing table created as **Task 12** of my
**Web Development Internship at Veda Technology**.

## 📌 Project Overview

This project is a responsive pricing table containing three plans.
Each plan displays a price, feature list, and call-to-action button.

The Pro plan is highlighted as the popular plan.

## 🎯 Objective

The objective of this task was to practice:

- CSS Flexbox
- CSS Grid
- Card layouts
- Hover effects
- Responsive design
- Spacing and typography

## 🛠️ Technologies Used

- HTML5
- CSS3

## ✨ Features

- Three pricing cards
- Basic plan
- Pro plan
- Premium plan
- Highlighted Popular plan
- Feature lists
- Call-to-action buttons
- Hover effects
- Responsive stacking
- Clean card-based layout

## 💳 Pricing Plans

### Basic

- ₹299/month
- 1 User
- 5 Projects
- Basic Support
- 5 GB Storage
- Basic Analytics

### Pro

- ₹699/month
- 5 Users
- 20 Projects
- Priority Support
- 50 GB Storage
- Advanced Analytics

### Premium

- ₹1299/month
- Unlimited Users
- Unlimited Projects
- 24/7 Support
- 200 GB Storage
- Advanced Analytics

## ⭐ Popular Plan

The Pro plan is visually highlighted using:

- A stronger border
- A Popular badge
- Elevated card position
- Different button styling

This makes the featured plan visually distinct from the other plans.

## 📐 Layout

CSS Grid is used to arrange the three pricing cards:

```css
.pricing-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
