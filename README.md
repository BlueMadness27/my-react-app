# 💸 Simple Expense Tracker (React + TypeScript + Vite)

This is Phase 1 of a multi-stage project designed to help me learn **TypeScript**, **React**, **component structure**, **state management**, and **API-ready architecture**.  
The goal is to start with something simple and expand it into a full-featured, real-world application.

This project is built using:

- ⚛️ React  
- 🟦 TypeScript  
- ⚡ Vite  
- 🎨 Custom UI (no external UI libraries yet)

---

## 📌 Phase 1: Basic Functionality (Completed)

Phase 1 includes:

### ✔ Add New Expenses  
- Description  
- Amount  
- Category (Food, Transport, Shopping, Bills, Other)  
- Date  
- Automatically generated ID  

### ✔ Display Expenses  
A clean table that shows each entry:

- Date  
- Description  
- Category  
- Amount  

### ✔ Total Calculations  
The app automatically calculates:

- Total number of expenses  
- Total amount spent  

### ✔ Fully Typed with TypeScript  
The project uses custom types:

```ts
type Category = "Food" | "Transport" | "Shopping" | "Bills" | "Other";

interface Expense {
  id: number;
  description: string;
  amount: number;
  category: Category;
  date: string;
}
