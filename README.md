# Project Genesis: Text-to-Website Generator 🌐

**Project Genesis** is an innovative tool that transforms natural language descriptions into a fully functional static website. Powered by intelligent parsing and code generation, it aims to democratize web development by allowing anyone to create a professional-looking website with simple text input.

---

### ✨ Features

* **Natural Language Understanding:** Describe your desired website in plain English.
* **Dynamic Website Types:** Generate websites for various purposes:
    * 🛍️ **E-commerce:** `cửa hàng` (store)
    * 🍽️ **Restaurant:** `nhà hàng`
    * 🏢 **Corporate:** `công ty`
    * 👤 **Personal/Portfolio:** `cá nhân`
    * 📝 **Blog:** `blog`
* **Customizable Colors:** Specify primary colors by name (e.g., `red`, `blue`, `pink`).
* **Automatic Section Generation:** Includes common sections like Header, Hero, About, Contact, and Footer, with conditional sections based on your description (e.g., Products, Menu, Services, Portfolio, Blog, Gallery).
* **Responsive Design:** Generated websites are built with a modern, responsive layout using basic CSS for adaptability.
* **Interactive Elements:** Basic JavaScript for smooth scrolling, mobile navigation toggle, and simulated form submission.
* **Downloadable Source Code:** Get a `.zip` file containing `index.html`, `styles.css`, and `script.js` ready for deployment.

---

### 🚀 How to Use

1.  **Run the Streamlit App:**
    Make sure you have Streamlit installed (`pip install streamlit`).
    Navigate to the directory containing `geneweb.py` in your terminal and run:
    ```bash
    streamlit run geneweb.py
    ```
2.  **Describe Your Website:**
    In the text area provided, enter a detailed description of the website you want to create.

    **Examples:**
    * `"Create an e-commerce website named 'TechGadget Shop' with a blue primary color. It needs product pages, an about section, and a contact form."`
    * `"I want a personal portfolio site for 'Jane Doe' in purple. Include a portfolio section and a contact page."`
    * `"Build a blog called 'My Travel Adventures' with a green theme. I need a blog posts section and an about page."`
3.  **Generate & Download:**
    Click the "Tạo Website" (Generate Website) button. The app will process your request, display the generated specification and code, and provide a download button for the `.zip` archive.
4.  **Deploy (Optional):**
    Unzip the downloaded file. You can open `index.html` in your browser to preview the site locally. For online deployment, consider platforms like Vercel, Netlify, or GitHub Pages.

---

### 🛠️ Technologies Used

* **Python:** Backend logic and Streamlit application.
* **Streamlit:** For the interactive web UI.
* **HTML5:** Website structure.
* **CSS3:** Styling and responsiveness.
* **JavaScript:** Interactive client-side functionality.
* **Font Awesome:** Icons.

---

### 💡 Future Enhancements (AI Integration - *Conceptual*)

The full vision for Project Genesis includes advanced AI capabilities:

* **Advanced NLP:** Deeper understanding of complex user prompts, including nuances in tone, brand identity, and specific content requirements.
* **LLM-driven Content Generation:** Using Large Language Models (LLMs) to automatically generate placeholder text, descriptions, and even initial blog posts based on the website's theme.
* **AI-powered Design Suggestions:** Recommending color palettes, font pairings, and layout variations based on best practices and user preferences.
* **Image Generation/Selection:** Integrating AI image generation (e.g., Stable Diffusion, Midjourney API) to create relevant placeholder images or suggest stock photos.
* **Framework Agnosticism:** Ability to generate code for various front-end frameworks (e.g., React, Vue, Angular) and CSS frameworks (e.g., Tailwind CSS, Bootstrap).
* **Backend Integration:** Generating basic backend stubs or integrating with headless CMS solutions for dynamic content management.
* **Direct Deployment Integration:** Streamlined one-click deployment to popular hosting providers like Vercel, AWS Amplify, or Netlify.

---

Tuyệt vời! Thêm một giấy phép là một bước quan trọng để xác định cách người khác có thể sử dụng mã của bạn.

Thêm Giấy phép MIT vào Project Genesis
Để thêm Giấy phép MIT vào dự án của bạn, bạn cần tạo một tệp mới có tên LICENSE (không có phần mở rộng) trong thư mục gốc của dự án và dán nội dung giấy phép vào đó.

Dưới đây là nội dung của Giấy phép MIT mà bạn có thể dán vào tệp LICENSE của mình:

## MIT License

Copyright (c) [2025] [UTH]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
