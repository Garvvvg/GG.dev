# Modern Portfolio Site 🚀

This project is a modern and responsive portfolio website built with React and Vite. It showcases my skills, education, projects, and certifications, providing a professional online presence. The site includes a contact form, smooth animations, and a clean, user-friendly design. It's designed to be easily customizable and deployable.

## ✨ Key Features

- **Responsive Design:** Adapts seamlessly to different screen sizes (desktop, tablet, mobile).
- **Interactive UI:** Engaging user experience with animations and transitions using `framer-motion`.
- **Modular Components:** Well-structured components for easy maintenance and customization.
- **Skills Showcase:** Clearly displays your technical skills with icons and categories.
- **Project Portfolio:** Highlights your projects with descriptions, technologies, and links to live demos and GitHub repositories.
- **Education Timeline:** Presents your education history in a visually appealing timeline format.
- **Contact Form:** Allows visitors to send you messages directly from the website.
- **Vercel Analytics:** Tracks website usage and provides insights into visitor behavior.
- **Particle Background:** Adds a visually appealing particle effect to the hero section.
- **Scroll-to-Top Functionality:** Provides a convenient way to navigate back to the top of the page.

## 🛠️ Tech Stack

| Category      | Technology                                  | Description                                                                 |
|---------------|---------------------------------------------|-----------------------------------------------------------------------------|
| **Frontend**  | React                                       | Core library for building the user interface                               |
|               | TypeScript                                  | Adds static typing to JavaScript for improved code quality                 |
|               | Tailwind CSS                                | CSS framework for styling the application                                  |
|               | Framer Motion                               | Animation library for creating smooth transitions and effects               |
|               | Lucide React                                | Icon library for consistent and visually appealing icons                   |
|               | React Icons                                 | Icon library for various technologies                                       |
|               | React Intersection Observer                 | Detects when an element is visible in the viewport                           |
|               | React Tsparticles                           | React wrapper for the `tsparticles` library                                |
|               | Tsparticles                                 | Library for creating particle effects                                       |
| **Backend**   | EmailJS                                     | Service for sending emails from the browser                                 |
| **Build Tool**| Vite                                        | Fast and lightweight build tool                                             |
| **Analytics** | Vercel Analytics                            | Tracks website usage and provides insights into visitor behavior             |
| **Other**     | ESLint                                      | JavaScript linter for code quality                                          |
|               | Prettier                                    | Code formatter for consistent code style                                    |
|               | PostCSS                                     | Tool for transforming CSS with JavaScript                                   |

## 📦 Getting Started

Follow these steps to set up the project locally:

### Prerequisites

- Node.js (>=18)
- npm or yarn

### Installation

1.  Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2.  Navigate to the project directory:

    ```bash
    cd modern-portfolio-site
    ```

3.  Install dependencies:

    ```bash
    npm install # or yarn install
    ```

4.  Configure EmailJS (optional, for the contact form):

    - Create an account on [EmailJS](https://www.emailjs.com/).
    - Create a new service and template.
    - Set the following environment variables in a `.env` file:

        ```
        VITE_EMAILJS_SERVICE_ID=<your_service_id>
        VITE_EMAILJS_TEMPLATE_ID=<your_template_id>
        VITE_EMAILJS_PUBLIC_KEY=<your_public_key>
        ```

### Running Locally

1.  Start the development server:

    ```bash
    npm run dev # or yarn dev
    ```

2.  Open your browser and navigate to `http://localhost:5173` (or the port specified in the console).

## 💻 Project Structure

```
modern-portfolio-site/
├── src/
│   ├── _components/
│   │   ├── About.tsx
│   │   ├── AnimatedText.tsx
│   │   ├── Certifications.tsx
│   │   ├── Contact.tsx
│   │   ├── Education.tsx
│   │   ├── FadeInView.tsx
│   │   ├── Footer.tsx
│   │   ├── Hero.tsx
│   │   ├── Navbar.tsx
│   │   ├── ParticleBackground.tsx
│   │   ├── Projects.tsx
│   │   ├── ScrollToTop.tsx
│   │   ├── Skills.tsx
│   │   └── Toast.tsx
│   ├── App.tsx
│   ├── index.css
│   ├── main.tsx
│   └── vite-env.d.ts
├── .eslintrc.cjs
├── .gitignore
├── index.html
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── tsconfig.json
├── tsconfig.node.json
└── vite.config.ts
```

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your fork.
5.  Submit a pull request to the main repository.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact

If you have any questions or suggestions, feel free to contact me at [garvg2005@gmail.com](mailto:garvg2005@gmail.com).

## 💖 Thanks

Thank you for checking out this project! I hope it helps you create a stunning online portfolio.
