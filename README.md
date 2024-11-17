Here’s a revised version of the README to better align with a professional tone and project-specific details:

---

# **Mini CRM & Campaign Management App**

This is a **Next.js** project, bootstrapped with `create-next-app`. The application enables users to manage customer data, define audience segments, run campaigns, and track their performance.

---

## **Getting Started**

### **Development Server**

To start the development server, run one of the following commands in your terminal:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Once the server is running, open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

The app supports **hot-reloading**, so any changes you make to the code will automatically reflect in the browser.

---

## **Project Structure**

- `app/page.js`: Main entry point for editing the homepage.
- `components/`: Contains reusable UI components for building the interface.
- `pages/`: Directory for application routes.
- `public/`: Static assets such as images, icons, and fonts.
- `styles/`: Contains global and modular CSS/SCSS files.

---

## **Features**

1. **Audience Creation:**
   - Create audience segments using conditions like total spending, visit count, and inactivity duration.
   - Apply **AND/OR** logic to filter data dynamically.
   - Display audience size before saving the segment.

2. **Campaign History & Stats:**
   - View past campaigns, sorted by the most recent.
   - Display detailed statistics (audience size, sent/failed messages, etc.).

3. **Message Sending:**
   - Save audience data in a `communications_log` table.
   - Send personalized messages using a dummy API.
   - Simulate message delivery with randomized statuses (90% SENT, 10% FAILED).

4. **Google Authentication:**
   - Secure access to the web app using Google-based login.

5. **Pub-Sub Model (Bonus):**
   - Efficient batch database updates for communication status.

---

## **Installation**

### Prerequisites
- Node.js (version 14.x or higher)
- npm, yarn, or pnpm for dependency management.

### Steps:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <project-directory>
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

---

## **Fonts & Optimization**

This project uses `next/font` for automatic optimization and loading of the **Geist** font family by Vercel.

---

## **Deployment**

The easiest way to deploy this Next.js app is by using the **Vercel Platform**. Follow the [Next.js Deployment Documentation](https://nextjs.org/docs/deployment) for detailed steps.

---

## **Resources**

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and APIs.
- [Learn Next.js](https://nextjs.org/learn) - Interactive tutorial to get started with Next.js.
- [Next.js GitHub Repository](https://github.com/vercel/next.js) - Feedback and contributions are welcome.

---

Feel free to update this README with project-specific customizations as needed.
