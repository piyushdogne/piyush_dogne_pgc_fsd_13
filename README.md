# **Book Management App**

A React-based application for managing and exploring a collection of books. Users can add new books, browse through newly added books, and fetch detailed information about books either from local storage or an external API.

---

## **Features**

- **Add a New Book**:
  - Users can add a new book by providing details such as the title, author, category, description, rating, and an optional cover image from their desktop.
  - Books are assigned a unique ID using `crypto.randomUUID()`.

- **Browse Newly Added Books**:
  - View the list of all books added via the app.
  - If no cover image is provided, a placeholder message ("No Cover") is displayed.

- **Fetch Book Details**:
  - Fetch book details from local storage if the book exists.
  - If the book is not found locally, fetch its details from the Open Library API.

- **Responsive UI**:
  - Fully responsive design with elegant gradients, shadows, and focus styles for a modern user experience.
  - Utilizes CSS utilities like TailwindCSS for styling.

---

## **Tech Stack**

- **Frontend**: React, Redux Toolkit
- **Backend/API**: Open Library API (for fetching book details)
- **Styling**: TailwindCSS
- **Storage**: Local Storage (for saving user-added books)

---

## **Setup Instructions**

### **Prerequisites**

Ensure you have the following installed:
- **Node.js** (v14+)
- **npm** or **yarn**

### **Steps**

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/book-management-app.git
   cd book-management-app

#   p i y u s h _ d o g n e _ p g c _ f s d _ 1 3 
 
 
