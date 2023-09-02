# tailwind-project
**hosted link** :-https://thakaresakshi.github.io/tailwind-project/

1. **External Dependencies**:

   - The code includes external CSS dependencies using `<link>` tags. These dependencies include:
     - **animate.css**: This is a CSS library that provides various pre-built animations.
     - **Material Icons**: This link is used to load Google's Material Icons font.
     - **Tailwind CSS**: The code uses Tailwind CSS, but the CSS file is likely located at "./dist/output.css," so it is linked here.

2. **Body Class**:

   - `class="bg-black font-sans"`: These classes set the background color to black and specify a sans-serif font for the entire `<body>` element.

3. **Header Section**:

   - The `<header>` section contains a navigation bar with a logo and social media icons. It uses various Tailwind CSS classes like `w-full`, `flex`, `justify-between`, and `text-white` to style the navigation bar.
![image](https://github.com/ThakareSakshi/tailwind-project/assets/86354291/5f0840f3-951d-4af3-9e06-ee5a22a61759)

4. **Main Section**:

   - **Hero Section**: This section displays a hero image with text content on top of it.
     - `bg-top bg-cover` is used to set the background image and apply styles to it.
     - The text content is centered and styled using Tailwind CSS classes such as `text-5xl`, `font-bold`, and `text-white`.
     - A button is styled using classes like `bg-transparent`, `border-2`, `py-4`, and `rounded-md`.
       
![image](https://github.com/ThakareSakshi/tailwind-project/assets/86354291/58f762a0-8a1e-448e-b85e-350f80d6e7c6)

   - **About Section**: This section contains two columns, one with an image and the other with text.
     - The image is styled using classes like `rounded-lg`, `overflow-hidden`, and `object-cover`.
     - Text content is styled using various classes like `text-white`, `font-sans`, and `text-xl`.
     - Icon elements use Font Awesome classes like `fa-solid` and `fa-dumbbell` to display icons.

![image](https://github.com/ThakareSakshi/tailwind-project/assets/86354291/35377fcf-85c5-4a22-9015-250e0e8e221a)

5. **Trainers Section**:

   - This section displays trainer profiles with images and text.
   - Each trainer profile uses classes like `flex`, `flex-col`, `p-2`, and `rounded-md` for styling.
   - AOS (Animate On Scroll) is used for animations. For example, `data-aos="flip-left"` triggers a flip-left animation when the element scrolls into view.

![image](https://github.com/ThakareSakshi/tailwind-project/assets/86354291/91e02fb5-b17f-49bf-8f79-7d7904d11829)

![image](https://github.com/ThakareSakshi/tailwind-project/assets/86354291/5b2cc295-e212-4f0f-aaa0-27e844159a70)



6. **Contact Section**:

   - This section contains a contact form.
   - The form elements are styled using classes like `rounded-md`, `border-2`, and `text-black`.
   - AOS is used for animations, such as `data-aos="fade-up-right"` for the form.

7. **Footer Section**:

   - The footer section contains social media icons and copyright information.
   - Social media icons are styled with Font Awesome classes.
   - The `clip-path` property is used to create a non-rectangular shape for the footer.

8. **JavaScript**:

   - The code includes JavaScript for AOS initialization (`AOS.init()`), which sets up the Animate On Scroll library with specific settings like delay and duration for animations.

Overall, the code utilizes Tailwind CSS classes for styling and incorporates animations from the animate.css library and AOS for a visually appealing and interactive web page.
