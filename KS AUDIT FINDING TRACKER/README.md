[tailwind.config.js](https://github.com/user-attachments/files/31387661/tailwind.config.js)
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {
      colors: {
        brand: {
          50: '#f0f7ff',
          100: '#e0effe',
          500: '#1d4ed8',
          600: '#1e40af',
          700: '#1e3a8a',
          800: '#172554',
          900: '#0f172a',
        },
        audit: {
          high: '#ef4444',
          medium: '#f97316',
          low: '#22c55e',
          overdue: '#dc2626',
          closed: '#16a34a',
          open: '#ea580c',
          pending: '#2563eb',
          draft: '#6b7280',
        }
      }
    },
  },
  plugins: [],
}
